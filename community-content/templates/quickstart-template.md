---
title: "Quickstart: [verb] * [noun]" #Required; page title displayed in search results. Include the word "quickstart". Include the brand.
description: [Article description.] #Required; article description that is displayed in search results. Include the word "quickstart".
author: carlyrevier #Required; your GitHub user alias, with correct capitalization.
ms.author: mlcc-owners #Required; a Microsoft distribution list; don't change. 
ms.service: azure #Required; request from Microsoft admin.
ms.topic: quickstart #Required; don't change.
ms.date: 06/16/2023 #Required; mm/dd/yyyy format.
contributor-type: community #Required; don't change.
content_well_notification: 
  - Human-created-Community
---

<!--
Remove all the comments in this template before you sign-off or merge to the 
main branch.

This template provides the basic structure of a Quickstart - General article pattern. This template provides the basic structure of a Quickstart article pattern. Refer to the [style and voice quick start article in the contributor guide](https://learn.microsoft.com/contribute/style-quick-start).

Quickstarts are fundamental day-1 instructions for helping new customers use 
a subscription to quickly try out a specific product/service. The entire activity 
is a short set of steps that provides an initial experience.

You only use quickstarts when you can get the service, technology, or functionality 
into the hands of new customers in less than 10 minutes.

-->

# Quickstart: [verb] * [noun]

<!-- Required: Article headline - H1

Identify the product or service and the feature area
the quickstart covers.

-->

---

**Principal author**: [Your name](URL of your Microsoft Learn profile)

---

[Introduce and explain the purpose of the article.]

<!-- Required: Introductory paragraphs (no heading)

Write a brief introduction that can help the user determine whether the article is relevant for them. Begin with a sentence that says, "In this quickstart, you..."

-->

If you don't have a service subscription, create a free trial account...

<!-- Required: Free account links (no heading)

Because quickstarts are intended to help new customers use a product or service, include a link to a  free trial before the first H2.

-->

## Prerequisites

<!-- Required: Prerequisites - H2

"Prerequisites" must be the first H2 in the article.

List any items that are needed for the quickstart, such as permissions or software.

If the user needs to sign in to a portal to do the quickstart, provide instructions and a link.

If there aren't any prerequisites, in a new paragraph under the "Prerequisites" H2, enter "None" in plain text (not as a bulleted list item).

-->

- An Azure account with an active subscription. [Create an account for free](https://azure.microsoft.com/free/?WT.mc_id=A261C142F).
- (Optional: Completion of a previous quickstart if the current one depends on it. Use the language "Completion of (title)" where (title) is the link.)
- First prerequisite
- Second prerequisite
- Third prerequisite
- ...
- (Any specific service-specific key - if specific actions are required, either link to an article that explains those steps, or make acquisition of a key one of the steps in the quickstart.)

## Open [Cloud Shell, Azure CLI, or PowerShell]

<!-- Optional: Open a demo environment - H2

If you want to refer to using Azure Cloud Shell, the Azure CLI, or Azure PowerShell, place the instructions after the "Prerequisites" section.

Include Cloud Shell only if all commands can run in Cloud Shell.

--->

## [verb] * [noun]

[Introduce a task and its role in completing the process.]

<!-- Required: Tasks to complete in the process - H2

In one or more numbered H2 sections, describe tasks that the user completes in the process the quickstart describes.

-->

1. Procedure step
1. Procedure step
1. Procedure step

<!-- Required: Steps to complete the tasks - H2

Use ordered lists to describe how to complete tasks in the process. Be consistent when you describe how to use a method or tool to complete the task.

Code requires specific formatting. Here are a few useful examples of commonly used code blocks. Make sure to use the interactive functionality when possible.

For the CLI-based or PowerShell-based procedures, don't use bullets or numbering.

Here is an example of a code block for Java:

```java
cluster = Cluster.build(new File("src/site.yaml")).create();
...
client = cluster.connect();
```

Here's a code block for the Azure CLI:

```azurecli-interactive 
az vm create --resource-group myResourceGroup --name myVM 
--image win2016datacenter --admin-username azureuser 
--admin-password myPassword12
```

This is a code block for Azure PowerShell:

```azurepowershell-interactive
New-AzureRmContainerGroup -ResourceGroupName 
myResourceGroup -Name mycontainer 
-Image mcr.microsoft.com/windows/servercore/iis:nanoserver 
-OsType Windows -IpAddressType Public
```
-->

## Clean up resources

<!-- Optional: Steps to clean up resources - H2

Provide steps the user takes to clean up resources that were created to complete the article.

-->

## Next step -or- Related content

> [!div class="nextstepaction"]
> [Next sequential article title](link.md)

-or-

- [Related article title](link.md)
- [Related article title](link.md)
- [Related article title](link.md)

<!-- Optional: Next step or Related content - H2

Consider adding one of these H2 sections (not both):

A "Next step" section that uses 1 link in a blue box 
to point to a next, consecutive article in a sequence.

-or- 

If the quickstart is not part of a sequence, use a 
"Related content" section that lists links to 
1 to 3 articles the user might find helpful.

-->

<!--

Remove all comments except the customer intent
before you sign off or merge to the main branch.

-->
