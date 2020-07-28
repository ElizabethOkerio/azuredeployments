# azuredeployments
To deploy run the following commands
az login
az account set --subscription "subscription name/sibscription id"
az group create --name "resource group name" --location "Central US"  
az deployment group create --name "resource group deployment name" --resource-group "the name of the resource group you created" --template-file "path-to-template-file" --parameters "path-to-parameters-file"
