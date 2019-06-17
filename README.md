---
services: Compute
platforms: java
author: yaohaizh
---

## Getting Started with Compute - Manage User Assigned MSI Enabled Virtual Machine - in Java ##


  Azure Compute sample for managing virtual machines -
   - Create a Resource Group and User Assigned MSI with CONTRIBUTOR access to the resource group
   - Create a Linux VM and associate it with User Assigned MSI
       - Install Java8, Maven3 and GIT on the VM using Azure Custom Script Extension
   - Run Java application in the MSI enabled Linux VM which uses MSI credentials to manage Azure resource
   - Retrieve the Virtual machine created from the MSI enabled Linux VM.
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-user-assigned-msi-enabled-virtual-machine.git

    cd compute-java-manage-user-assigned-msi-enabled-virtual-machine

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.