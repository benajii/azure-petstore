# azure-petstore
My azure Pet store project

## Additional Documentation Used 
### Step 0
- [convert JSON to Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/decompile?tabs=azure-cli)
    - I used this to gain experiance writing and reading bicep files.
- [Azure Button](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/deploy-to-azure-button)
    - this is a simple and quick link to deploy a template
### Step 1
- [Query IP of contain from CLI](https://docs.docker.com/engine/reference/commandline/inspect/)
    - the command to query the container included a typo in calling the container image, use the container name without the ':Latest'

## Resouces Used
- Firstly this project was guided by [chtrembl](https://chtrembl.github.io/azure-cloud/petstore/). Thank you for creating this educational guide.
- I converted [this](https%3A%2F%2Fraw.githubusercontent.com%2Fchtrembl%2Fazure-cloud%2Fmain%2Fpetstore%2F00-setup-your-environment%2Fazuredeploy.json) template to Bicep and included paremeters for Names and region, see all deployment files in the [bicep folder](https://github.com/benajii/azure-petstore/tree/main/bicepfiles). 
- Azure button isnt currently supported for bicep so this is the ARM Template [![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbenajii%2Fazure-petstore%2Fmain%2Fbicepfiles%2Ftemplate.json)