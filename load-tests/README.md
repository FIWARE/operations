# FIWARE Load Tests

![License](https://img.shields.io/github/license/fiware/load-tests)

Load tests to run against installations of FIWARE Components - NGSI Context Brokers running on scalable test architecture scenarios and installed with and without additional FIWARE microservices.

| :octocat: [Git Repository](https://github.com/FIWARE/load-tests) |
| ---------------------------------------------------------------- |

### What is FIWARE Load Tests?

Gatling load tests to run against FIWARE Components that implement the NGSI-LD API. The repository also includes test-reports for various setups of different FIWARE Components.

### Why use FIWARE Load Tests?

When creating FIWARE infrastructure, it is important to understand how and where bottlenecks occur, and how to allieviate them at minimal cost. 
These load tests are able to reproduce consistent throughputs on simple FIWARE systems, and therefore openly demonstrate an acceptable rate of 
requests to send to a context brokers or a federation. If your own installation is much slower or unable to match these ratings then it should confirm
that the current architecture is suboptimal

Similarly, when considering scaling up an installation, the existing test results should help to understand when more CPU or virtual rack space
is really required, and when other simpler optimisations such as improving indexing will help.
