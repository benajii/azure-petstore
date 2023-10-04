# azure-petstore
My azure Pet store project

## Documentation Used
- [convert JSON to Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/decompile?tabs=azure-cli)
- [Azure Button](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button)

## Resouces Used
-   I converted [this](https%3A%2F%2Fraw.githubusercontent.com%2Fchtrembl%2Fazure-cloud%2Fmain%2Fpetstore%2F00-setup-your-environment%2Fazuredeploy.json) template to Bicep and included paremeters for Names and region, see all deployment files in the [bicep folder](https://github.com/benajii/azure-petstore/tree/main/bicepfiles). Azure button isnt currently supported for bicep so this is the ARM Template [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbenajii%2Fazure-petstore%2Fmain%2Fbicepfiles%2Ftemplate.json)