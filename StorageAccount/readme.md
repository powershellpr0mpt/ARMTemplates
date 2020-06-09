# Easily deploy Log Analytics Workspace solution directly to Azure

This ARM Template will create a storage account.

When using this ARM template, it will also provide the following features:

* Automatically set it to type [Standard_LRS][storageSku]
* Enable HTTPS traffic
* Set Encryption

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3a%2f%2fraw.githubusercontent.com%2fpowershellpr0mpt%2fARMTemplates%2fmaster%2fStorageAccount%2fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>

[storagSku]: https://docs.microsoft.com/en-us/azure/storage/common/storage-account-overview#redundancy