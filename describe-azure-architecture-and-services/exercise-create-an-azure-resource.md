# Exercise - Create an Azure Resource

https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/7-exercise-create-azure-resource

This module requires a sandbox to complete. You have used 1 of 10 sandboxes for today. More sandboxes will be available tomorrow.

In this exercise, you’ll use the Azure portal to create a resource. The focus of the exercise is observing how Azure resource groups populate with created resources.

Important:
The sandbox should already be activated, but if the sandbox closed, reactivate the sandbox before continuing.

## Task 1: Create a virtual machine

In this task, you’ll create a virtual machine using the Azure portal.

1. Sign in to the Azure portal.

2. Select Create a resource > Compute > Virtual Machine > Create.

3. The Create a virtual machine pane opens to the basics tab.

4. Verify or enter the following values for each setting. If a setting isn’t specified, leave the default value.

Start with an Azure free trail:
free services: https://portal.azure.com/#view/Microsoft_Azure_Billing/FreeServicesBlade
I have created a VM by following the Settings on the table which has used a bit of my $200 training credit.

## Task 2: Verify resources created

Once the deployment is created, you can verify that Azure created not only a VM, but all of the associated resources the VM needs.

1. Select Home
2. Select Resource groups
3. Select the learn-4f4096cd-31cd-416b-a675-5f30e8ffab17 resource group

You should see a list of resources in the resource group. The storage account and virtual network are associated with the Learn sandbox. However, the rest of the resources were created when you created the virtual machine. By default, Azure gave them all a similar name to help with association and grouped them in the same resource group.

Congratulations! You've created a resource in Azure and had a chance to see how resources get grouped on creation.

## Clean up

The sandbox automatically cleans up your resources when you're finished with this module.

When you're working in your own subscription, it's a good idea at the end of a project to identify whether you still need the resources you created. Resources that you leave running can cost you money. You can delete resources individually or delete the resource group to delete the entire set of resources.

## Next unit: Knowledge check

https://learn.microsoft.com/en-us/training/modules/describe-core-architectural-components-of-azure/8-knowledge-check
