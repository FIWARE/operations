# FIWARE Marinera

![License](https://img.shields.io/github/license/fiware-ops/marinera)

A [GitOps](https://www.redhat.com/en/topics/devops/what-is-gitops) repository for deploying a FIWARE platform, using
[Kubernetes](https://kubernetes.io) and [Red Hat OpenShift](https://www.redhat.com/en/technologies/cloud-computing/openshift)

| :octocat: [Git Repository](https://github.com/FIWARE-Ops/marinera) |
| ------------------------------------------------------------------ |

### What is FIWARE Marinera?

Continuous Integration (CI) is a key practice of todays software development. the Marinera repo is configured to work with Github CI.
You can find the relevant CI workflows under the `.github/workflows` folder, in the root folder of the repository.

The CI workflows enable the creation of a new namespace based on any `feature-*` branch with the same name of the branch, and deploy
there the fiware-platform helm chart, which governs all the components of the FIWARE platform. This is implemented creating an ArgoCD
application per application defined in the repo.

### Why use FIWARE Marinera?

Automating deployments using CI eliminates error prone manual steps from the set-up process and enables changes to be swiftly tested and
brought into production. The Marinera repo includes a wide variety of common FIWARE components and with little amendment should be able to 
form the backbone of the CI pipeline for your own FIWARE deployments to a scalable, production system.
