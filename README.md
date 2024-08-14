# Azure Edge Extensions

Azure Edge Extensions is a suite of sample software tools and solutions designed to help you take full advantage of the power of Azure's
edge computing platforms. From notebook playgrounds, to CI/CD, to model transpilers, to production ready IaC, Azure
Edge Extensions are all built with the goal of composition in mind. Fork and integrate the elements you need, and see
your solutions come to life.

> [!WARNING]  
> Not all Azure Edge Extensions are compatible with all released versions of Azure Arc or preview versions of Azure IoT Operations. Please review
> [AIO release notes](https://github.com/Azure/azure-iot-operations/releases) and notes in each extension project to confirm component compatibility.

## Design Philosophy

Azure Edge Extensions are all built with the same basic principles, echoing the Unix Philosophy:

* Solve one, narrow business problem really well
* Code for contributions, not machine optimization
* Use well defined interfaces that enable composition
* Create a reaction for every action
* Output is always human readable and machine parsable

## Getting Started

All Azure Edge Extensions follow a common naming convention and use repository tags so you know what technologies are in
the box. The two primary template formats are:

* `azure-edge-extensions-{product}-{process}-{technology}`
* `azure-edge-extensions-{technology}-{platform}`

Some examples are:

* `azure-edge-extensions-aio-iac-terraform` - Azure IoT Operations Infrastructure as Code written in Terraform
* `azure-edge-extensions-polyglotnotebooks-aio` - a Polyglot Notebook for Azure IoT Operations
* `azure-edge-extensions-devcontainer-aksee` - A Dev Container with AKS Edge Essentials preinstalled

To see all the available Azure Edge Extensions please see the [project documentation at our GitHub Pages site](https://azure-samples.github.io/azure-edge-extensions/), or do a [GitHub search for 'azure-edge-extensions'](https://github.com/search?q=azure-edge-extensions+in%3Aname&type=Repositories&org%3AAzureSamples).

# Contributing Tools and Solutions to Azure Edge Extensions

Contributing your own tool to the collection is easy:

* File a [tool submission](https://github.com/Azure-Samples/azure-edge-extensions/issues/new?template=TOOL_SUBMISSION.md) in this repository
* Work with us on repository naming in the comments of the tool submission
* Create your repository
* We'll add your tool to the Azure Edge Extensions index

That's it.

If you need help, have feedback or questions about the Azure Edge Extensions project, just file an [issue](https://github.com/Azure-Samples/azure-edge-extensions/issues), we'd love to hear from you! 
