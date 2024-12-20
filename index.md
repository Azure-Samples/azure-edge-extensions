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
|  Operations  |  [Azure IoT Operations - Local Observability with OpenTelemetry and GitOps](https://github.com/Azure-Samples/azure-edge-extensions-aio-observability-gitops)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-aio-observability-gitops?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aio-observability-gitops/tags) |  Sample for configuring [Azure IoT Operations Preview](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) with [OpenTelemetry](https://opentelemetry.io/docs/what-is-opentelemetry/) and local observability visualization on edge enabled through Flux GitOps |
|  Operations  |  [AKS Edge Essentials - Provisioning with TLS termination proxy](https://github.com/Azure-Samples/azure-edge-extensions-aksee-proxy-certs)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-aksee-proxy-certs?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aksee-proxy-certs/tags) |  Sample for Provisioning [AKS Edge Essentials](https://learn.microsoft.com/en-us/azure/aks/hybrid/aks-edge-overview) with configuration of a proxy requiring TLS termination |
|  Operations  |  [Azure IoT Hub File Upload to Azure Storage through Private Endpoint](https://github.com/Azure-Samples/azure-edge-extensions-iothub-fileupload-privatelink)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-iothub-fileupload-privatelink?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-iothub-fileupload-privatelink/tags) |  Documentation and sample to enable [Azure IoT Hub's file upload](https://learn.microsoft.com/azure/iot-hub/iot-hub-devguide-file-upload) functionality through an Azure Storage account with public Internet access disabled |
|  Operations  |  [Implementing ISA-95 with Azure IoT Operations: LNM & MQ](https://github.com/Azure-Samples/azure-edge-extensions-lnm-mq-isa95)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-lnm-mq-isa95?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-lnm-mq-isa95/tags) |  Sample implementation of [Azure IoT Layered Network Management](https://learn.microsoft.com/en-us/azure/iot-operations/manage-layered-network/overview-layered-network) as part of Azure IoT Operations based on ISA-95 layered networking model |
|  Dev Loop/Operations  |  [AIO Custom Workloads with Dapr Workflow](https://github.com/azure-Samples/azure-edge-extensions-aio-dapr-workflow)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-aio-dapr-workflow?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-aio-dapr-workflow/tags) |  This sample repository provides a blueprint implementation to use Dapr Workflow in [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) to develop and apply custom workloads and workflows |
|  Operations  |  [AIO Akri 3p Connector](https://github.com/azure-Samples/azure-edge-extensions-akri-operator-3p-connector)  | [![GitHub Tag](https://img.shields.io/github/v/tag/azure-samples/azure-edge-extensions-akri-operator-3p-connector?logo=github&label=version)](https://github.com/Azure-Samples/azure-edge-extensions-akri-operator-3p-connector/tags) |  This sample repository demonstrates how to use Akri Services to implement an Akri 3p Connector utilizing [Azure IoT Operations](https://learn.microsoft.com/en-us/azure/iot-operations/get-started/overview-iot-operations) |

# Contributing Tools and Solutions to Azure Edge Extensions

Contributing your own tool to the collection is easy:

* File a [tool submission](https://github.com/Azure-Samples/azure-edge-extensions/issues/new?template=TOOL_SUBMISSION.md)
* Work with us on repository naming in the comments of the tool submission
* Create your repository
* We'll add your tool or solution to the Azure Edge Extensions index

That's it.

If you need help, have feedback or questions about the Azure Edge Extensions project, just file an [issue](https://github.com/Azure-Samples/azure-edge-extensions/issues), we'd love to hear from you! 
