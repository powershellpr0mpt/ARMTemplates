# Easily deploy Log Analytics Workspace solution directly to Azure

This ARM Template will create a Log Analytics Workspace to Azure and will create an accompanying storage account for log storage.

When using this ARM template, it will also provide the following features:

* Automatically place the created resources in the same location as the used Resource Group location
* Automatically set Log Analytics workspace retention period (365 days instead of Azure default of 30 days)
  You can use the parameters to adjust this setting as required.
* Set a resource lock on both Log Analytics workspace and storage account to prevent accidental deletion
* Set the Log Analytics [SKU][LA-Sku] to Per-GB

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F100-blank-template%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>

[LA-Sku]: https://docs.microsoft.com/en-us/azure/templates/Microsoft.OperationalInsights/2015-11-01-preview/workspaces#sku-object