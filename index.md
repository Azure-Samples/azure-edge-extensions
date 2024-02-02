---
layout: home
title: Home
nav_order: 1
---

# Azure Edge Extensions

Azure Edge Extensions is a suite of sample software tools and solutions designed to help you take full advantage of the power of Azure's
edge computing platforms. From notebook playgrounds, to CI/CD, to model transpilers, to production ready IaC, Azure
Edge Extensions are all built with the goal of composition in mind. Fork and integrate the elements you need, and see
your solutions come to life.

## Design Philosophy

Azure Edge Extensions are all built with the same basic principles, echoing the Unix Philosophy:

* Solve one, narrow business problem really well
* Code for contributions, not machine optimization
* Use well defined interfaces that enable composition
* Create a reaction for every action
* Output is always human readable and machine parsable

## Tools and Solutions

|  Area  |  Name (Repo Link)  |  Version  |  Description  |
|----|----|----|----|
|  Exploration  |  [Azure IoT Operations through Polyglot Notebooks](https://github.com/Azure-Samples/azure-edge-extensions-polyglotnotebook-aio)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-polyglotnotebook-aio?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-polyglotnotebook-aio/tags) |  Polyglot Notebooks that demonstrate how to use [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) using Codespaces  |
|  Dev Loop  |  [K3D Debugging Dev Container for Azure IoT Operations](https://github.com/Azure-Samples/azure-edge-extensions-aio-dapr-net-devcontainer-k3d)  |  [![GitHub Tag](https://img.shields.io/github/v/tag/Azure-Samples/azure-edge-extensions-aio-dapr-net-devcontainer-k3d?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aio-dapr-net-devcontainer-k3d/tags)  |  [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) debugging dev container with [k3d](https://k3d.io/) and [DAPR](https://dapr.io/)  |
|  Dev Loop  |  [IoT Edge Object Model](https://github.com/Azure-Samples/azure-edge-extensions-iotedge-objectmodel-dotnet)  |  [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-iotedge-objectmodel-dotnet?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-iotedge-objectmodel-dotnet/tags)  |  This library provides extensions methods of the [Azure IoT SDK](https://learn.microsoft.com/en-us/azure/iot/iot-sdks). The object model supplies a common API to view and edit deployment manifests regardless of whether they originate from an At-Scale or single device deployment  |
|  IAC  |  [Terraform for Azure IoT Operations](https://github.com/Azure-Samples/azure-edge-extensions-aio-iac-terraform)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-aio-iac-terraform?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aio-iac-terraform/tags) |  Infrastructure as Code (IaC) [Terraform](https://www.terraform.io/) for [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) components. Includes initial infrastructure setup through Terraform  |
|  Operations  |  [IoT Edge Deployment Engine (.NET)](https://github.com/Azure-Samples/azure-edge-extensions-iotedge-deploymentengine-dotnet)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-iotedge-deploymentengine-dotnet?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-iotedge-deploymentengine-dotnet/tags) |  Deployment engine that provides enhanced experience and flexibility for the [Azure IoT Edge](https://learn.microsoft.com/en-us/azure/iot-edge/about-iot-edge) deployment processes  |
|  ML/AI  |  [Retrieval-Augmented Generation for Azure IoT Operations](https://github.com/Azure-Samples/azure-edge-extensions-retrieval-augmented-generation)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-retrieval-augmented-generation?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-retrieval-augmented-generation/tags) |  A sample RAG solution for [AKS Edge Essentials](https://learn.microsoft.com/en-us/azure/aks/hybrid/aks-edge-overview) and [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations)  |
|  Data Modeling  |  [ADT Model Management & Versioning](https://github.com/Azure-Samples/azure-edge-extensions-adt-modelmgmt) | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-adt-modelmgmt?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-adt-modelmgmt/tags) |  Azure Digital Twins (ADT) DTDL model management tools. Simplifies model uploading and updating through batch uploads and DAG validation  |
|  Data Modeling  |  [ADT Transpiler](https://github.com/Azure-Samples/azure-edge-extensions-adt-transpiler) | [![GitHub Tag](https://img.shields.io/github/v/tag/Azure-Samples/azure-edge-extensions-adt-transpiler?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-adt-transpiler/tags) |  Code-first transpiler to [DTDL](https://learn.microsoft.com/en-us/azure/digital-twins/concepts-models#digital-twin-definition-language-dtdl-for-models)  |
|  AIO Environments  |  [AIO Environments](https://github.com/Azure-Samples/azure-edge-extensions-aio-environments) | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-aio-environments?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aio-environments/tags) |  Platform to build Azure IoT Operations (AIO) environments  |

# Contributing Tools and Solutions to Azure Edge Extensions

Contributing your own tool to the collection is easy:

* File a [tool submission](https://github.com/Azure-Samples/azure-edge-extensions/issues/new?template=TOOL_SUBMISSION.md)
* Work with us on repository naming in the comments of the tool submission
* Create your repository
* We'll add your tool or solution to the Azure Edge Extensions index

That's it.

If you need help, have feedback or questions about the Azure Edge Extensions project, just file an [issue](https://github.com/Azure-Samples/azure-edge-extensions/issues), we'd love to hear from you! 
