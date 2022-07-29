---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Compute
  platforms: java
---

# Getting Started with Compute - Manage User Assigned MSI Enabled Virtual Machine - in Java #


  Azure Compute sample for managing virtual machines -
   - Create a Resource Group and User Assigned MSI with CONTRIBUTOR access to the resource group
   - Create a Linux VM and associate it with User Assigned MSI
       - Install Java8, Maven3 and GIT on the VM using Azure Custom Script Extension
   - Run Java application in the MSI enabled Linux VM which uses MSI credentials to manage Azure resource
   - Retrieve the Virtual machine created from the MSI enabled Linux VM.
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-manage-user-assigned-msi-enabled-virtual-machine.git

    cd compute-java-manage-user-assigned-msi-enabled-virtual-machine

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
