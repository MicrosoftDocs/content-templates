title: Deploy /<workload name> on an Azure virtual machine 
description: # Add a short description of the article, including keywords. List facts about what the product intends to do along with the targeted industry/business process. The description must include the product name and related use cases but refrain from using marketing jargon or campaigning statements.
author:
ms.author:
ms.topic:
ms.service:
ms.date:

# Deploy /<workload name> on a virtual machine 

<!-- Make sure the title has all of the appropriate keywords for search. -->

<!-- The introduction should cover a basic overview of the workload, such as:

Why deploy <workload> on Azure 
- Simplifies migration to the cloud 
- Optimizes the workload in these ways…. 
- Can be rapidly provisioned 
- Performance 

-->

## Architecture 

<!-- Add a Product/Solution specific Architecture diagram. The architecture diagram must be product associated and the VM (Virtual Machines) topology should match the above stated test conditions.--> 

## Components 

<!-- Add a list of links to more information on the discrete pieces of the architecture. The list below is just an example of the most common items, you might need to add or remove items based on your architecture diagram.--> 

<!-- Link to the normal AAC standard links for these (Azure service pages)--> 

- Virtual machine <!-- Provide description/context. Please also link [Linux VMs on Azure](/azure/architecture/reference-architectures/n-tier/linux-vm)  or [Windows VMs on Azure](/azure/architecture/reference-architectures/n-tier/windows-vm) (whichever the architecture is based on) in the sentence that follows this. -->
- Network – <!-- description/context -->
- PIP – <!-- description/context -->
- NSG – <!-- description/context -->
- Storage – <!-- description/context -->

## Compute sizing and drivers 

<!-- List of evaluated sizes for this workload and a table of the input sizes with corresponding evaluated output for the chosen input sizes. --> 

### Required drivers 

<!-- Information about any specialized drivers required for the recommended sizes. List the specific size and link it to the appropriate page in the VM sizes documentation – for example: https://docs.microsoft.com/azure/virtual-machines/nda100-v4-series --> 

## /<Workload> installation 

Before you install <Workload>, you need to deploy and connect a VM and install the required NVIDIA and AMD drivers. 

> [!IMPORTANT]
> <!-- Optional. For example: NVIDIA Fabric Manager installation is required for VMs that use NVLink or NVSwitch. Delete this alert if not needed. -->

For information about deploying the VM and installing the drivers, see one of these articles: 

- [Run a Windows VM on Azure](/azure/architecture/reference-architectures/n-tier/windows-vm)
- [Run a Linux VM on Azure](/azure/architecture/reference-architectures/n-tier/linux-vm)

 
<!-- Must include a sentence or two to outline the installation context along with link/s (no internal links, it must be official/accessible) to install information of the product docs for the workload solution. Should not list any ordered steps of installation.--> 

## /<Workload> performance results 

<!--Give a short intro to how performance was tested --> 

<!-- Results for X --> 

<!-- Results for Y etc --> 

 ### Additional notes about tests 

<!-- Include any additional notes about the testing process used. --> 

## Azure cost 

<!-- Description of the costs that might be associated with running this workload in Azure. Make sure to have a link to the Azure pricing calculator.--> 

You can use the [Azure pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator/) to estimate the costs for your configuration. 

<!-- Show the pricing calculation or a direct link to this specific workload with the configuration(s) used. --> 

## Summary 

<!-- One or two sentences or bullet points reinforcing why Azure is the right platform for this workload --> 
