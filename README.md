# azuredeployments
To deploy run the following commands
az login </br>
az account set --subscription "subscription name/sibscription id" </br>
az group create --name "resource group name" --location "Central US" </br> 
az deployment group create --name "resource group deployment name" --resource-group "the name of the resource group you created" --template-file "path-to-template-file" --parameters "path-to-parameters-file" 
