---
title: #Required; page title displayed in search results. Start with a verb and include the terms "Azure" and "Terraform". Keep in mind the 65 char or less length suggestion.
description:  #Required; article description that is displayed in search results.
keywords: #Space-separated terms associated with article - include azure, devops, terraform.
ms.topic: #required; how-to, quickstart, tutorial, as appropriate.
author: #Required; your GitHub user alias, with correct capitalization.
ms.author: #Required; microsoft alias of author; optional team alias.
ms.date: #Required; mm/dd/yyyy format.
ms.custom: devx-track-terraform #Required
---

<!-- 
To write a Terraform article, follow the steps in this template and 
remove all HTML comments.
-->

<!--
General notes:

* Use the generic term "article" instead of "how-to", "tutorial", "quickstart", 
because as those terms are always subject to change.

This template provides the basic structure of a Terraform article pattern. See the
[instructions - Terraform](../level4/article-terraform.md) in the pattern library.

You can provide feedback about this template at: https://aka.ms/patterns-feedback

1. H1 ------------------------------------------------------------------------------
Required. Start with a verb and include the terms "Azure" and "Terraform". You can use
or expand on the title.

-->

# [Your H1 title including "Azure" and "Terraform"]
TODO: Add your heading.

<!-- 2. Terraform and Terraform provider information ------------------------------------
Required. Provide the Terraform and Terraform provider information. The code was
tested with these versions.

-->

Article tested with the following Terraform and Terraform provider versions:

- [Terraform vx.x.](https://releases.hashicorp.com/terraform/)
- [AzureRM Provider v.x.xx.x](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)

[Learn more about using Terraform in Azure](/azure/terraform)
TODO: Add version information.

<!-- 3. Introduction --------------------------------------------------------------------
Required. Introductory paragraph. Keep it short and to the point. 
Link to devhub index page of underlying technology where appropriate.

-->

TODO: Add introduction.

<!-- 4. Article checklist ---------------------------------------------------------------
Required. A checklist that summarizes what the reader does in the article.

-->

In this article, you learn how to:

> [!div class="checklist"]
> * Task 1
> * Task 2
> * Task n

TODO: Add article checklist.

<!-- 5. Link to example code ------------------------------------------------------------
Required. Use this note to link to the GitHub root directory of the source code.

-->

> [!NOTE]
> The example code in this article is located in the [Azure Terraform GitHub repo](https://github.com/Azure/terraform/tree/master/...).
TODO: Link to source code.

<!--
This template shows a standard example of H2 sections for a Terraform article:

## 1. Configure your environment
## 2. Implement the Terraform code
## 3. Initialize Terraform
## 4. Create a Terraform execution plan
## 5. Apply a Terraform execution plan
## 6. Verify the results
## 7. Clean up resources
## Troubleshoot Terraform on Azure
## Next steps

Your article might have additional sections that are not illustrated here. 

If you insert additional H2 sections not mentioned in this template, keep in mind the 
following guidelines:

* Every H2 should be of the form: "## n. <infinitive verb><action>"
* n is the sequential number of the section.
* Use sentence casing and no ending period.
* The first section should always be "## 1. Configure your environment".
* The section to implement the code should be called 
  "## n. Implement the Terraform code".
* If you insert other H2 sections, update the numbering shown in this 
  template accordingly.

-->

<!-- 6. Configure your environment section ----------------------------------------------
Required. The included files are bulleted lists. 

Add bullets for any article-specific includes or download/install URLs and commands.

NOTE: Numbering the list doesn't work with the include files.

-->

## 1. Configure your environment

[!INCLUDE [open-source-devops-prereqs-azure-subscription.md](../includes/open-source-devops-prereqs-azure-subscription.md)]

[!INCLUDE [configure-terraform.md](includes/configure-terraform.md)]
TODO: Add section.

<!-- 7. Implement the Terraform code section --------------------------------------------
Required. All Terraform procedural articles (tutorial, how-to) should have a minimum
of 4 files:

* providers.tf - declares the provider block
* main.tf -  declares resource group and your other code resources
* variables.tf - defines resource group name prefix, location, and any other variables
  that you need
* output.tf - outputs randomly generated resource group name

-->

## 2. Implement the Terraform code

1. Create a directory in which to test and run the sample Terraform code and make it the current directory.

1. Create a file named `providers.tf` and insert the following code:

    [!code-terraform[master](<!-- relative path from defined repo root to providers.tf-->)]
    <!--
    EXAMPLE: [!code-terraform[master](../../terraform_samples/quickstart/101-resource-group/providers.tf)]
    -->

1. Create a file named `main.tf` and insert the following code:

    [!code-terraform[master](<!-- relative path from defined repo root to main.tf-->)]
    <!--
    EXAMPLE: [!code-terraform[master](../../terraform_samples/quickstart/101-resource-group/main.tf)]
    -->

1. Create a file named `variables.tf` and insert the following code:

    [!code-terraform[master](<!-- relative path from defined repo root to variables.tf-->)]
    <!--
    EXAMPLE: [!code-terraform[master](../../terraform_samples/quickstart/101-resource-group/variables.tf)]
    -->

1. Create a file named `output.tf` and insert the following code:

    [!code-terraform[master](<!-- relative path from defined repo root to output.tf-->)]
    <!--
    EXAMPLE: [!code-terraform[master](../../terraform_samples/quickstart/101-resource-group/output.tf)]
    -->

<!--
If you have additional TF files, use the following 2 lines for each additional file. 

-->

1. Create a file named <!-- filename.tf --> and insert the following code:

    [!code-terraform[master](<!-- relative path from defined repo root to file -->)]
TODO: Add section.

<!-- 8. Initialize Terraform section ----------------------------------------------------
Required.

-->

## 3. Initialize Terraform

[!INCLUDE [terraform-init.md](includes/terraform-init.md)]
TODO: Add section.

<!-- 9. Create a Terraform execution plan -----------------------------------------------
Required.

-->

## 4. Create a Terraform execution plan

[!INCLUDE [terraform-plan.md](includes/terraform-plan.md)]
TODO: Add section.

<!-- 10. Apply a Terraform execution plan -----------------------------------------------
Required.

-->

## 5. Apply a Terraform execution plan

[!INCLUDE [terraform-apply-plan.md](includes/terraform-apply-plan.md)]
TODO: Add section.

<!-- 11. Apply the modified Terraform execution plan section ----------------------------
Optional. Use in cases where you have the customer create and apply a plan, followed by
making some changes, and now you want the customer to create and apply a new execution
plan based on the changes.
 NOTE: As with all the H2 section titles, you'll need to adjust the numbering.

-->

## N. Apply the modified Terraform execution plan

[!INCLUDE [terraform-plan-recreate.md](includes/terraform-plan-recreate.md)]
TODO: Add section.

<!-- 12. Verify the results -------------------------------------------------------------
Required. Customers have consistently requested that they have the ability to verify
whether the steps worked. Here you would specify steps to do that task.
For example, you might tell the user to run a specific command and what they should
see as output or go to the portal to view a resource that should have been created.

-->

## 6. Verify the results
TODO: Add section.

<!-- 13. Clean up resources section -----------------------------------------------------
Required. Describe how to reverse what the customer did in the article. 

In most cases, you need only include the file that shows the customer how to 
destroy the resources created previously.

However, in some more advanced cases, you might have the customer do more steps prior 
to implementing the code.

An example is the article to create a VMSS from a Packer image.

In that example, the customer creates the image, then implements and runs the code.

In situations like that, you include the same file as shown below and add the extra 
steps required to reverse any actions the customer did in creating Azure resources.

See the following example where H3 sections are used to separate each cleanup step:

https://docs.microsoft.com/azure/developer/terraform/create-vm-scaleset-network-disks-using-packer-hcl#8-clean-up-resources

-->

## 7. Clean up resources
[!INCLUDE [terraform-plan-destroy.md](includes/terraform-plan-destroy.md)]
TODO: Add section.

<!-- 14. Troubleshoot Terraform on Azure section ----------------------------------------
Required. This step should NOT be numbered.

-->

## Troubleshoot Terraform on Azure
[Troubleshoot common problems when using Terraform on Azure](troubleshoot.md)
TODO: Add section.

<!-- 15. Next steps section -------------------------------------------------------------
Required. Add only one URL.

If there is no logical next article, link to the Terraform home page, as shown here, or 
you can link to the home page for the Azure service being documented in your article.

-->

## Next steps

> [!div class="nextstepaction"] 
> [Learn more about using Terraform in Azure](/azure/terraform)

TODO: Add section.

<!-- Remove all HTML comments when you're done. -->