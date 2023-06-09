# FIWARE Operations

![FIWARE Catalogue](https://nexus.lab.fiware.org/repository/raw/public/badges/chapters/deployment-tools.svg)
[![License: MIT](https://img.shields.io/github/license/fiware/operations.svg)](https://opensource.org/licenses/MIT)

A collection of useful FIWARE Operations and deployment-related repositories such as Helm-Charts and reference architectures.

## Installation

To obtain the latest codebase of all FIWARE software related to Operations

```console
git clone https://github.com/FIWARE/operations.git
cd operations/
git submodule update --init --recursive
git submodule update --recursive --remote
```

## Projects

-  [FIWARE Helm Charts](./helm-charts) - for provisioning scalable, production-ready powered-by-FIWARE installations based around NGSI Context Brokers and other open source components
-  [FIWARE Load Tests](./load-tests) - to run against installations of FIWARE Components - NGSI Context Brokers running on scalable test architecture scenarios and installed with and without additional FIWARE microservices.
-  [FIWARE Marinera](./marinera) -  A GitOps repository for deploying a FIWARE platform, using Kubernetes and Red Hat OpenShift
-  [FIWARE GitOps](./fiware-gitops) - resource definitions for FIWARE-Kubernetes clusters
-  [ODALA](./odala) - enables the application of Machine Learning (ML), Deep Learning and Artificial Intelligence (AI) technology for 
   cities, based on the creation and demonstration of a ‘Data Lake’, which combines legacy city data with real-time data feeds.


## License

[MIT](LICENSE) © 2023 FIWARE Foundation e.V. 

This license applies to the infrastructure of this umbrella repository itself.
Each project is an imported submodule and holds a separate license agreement.
