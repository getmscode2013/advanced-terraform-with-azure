Lab 1::
A. Login to Azure

In this objective. you will us the credetials provided by lab to log into Azure using the Azure credetials

1. Open terminal and run *az login* comman
2. In browser window that open, enter the credentails provided in lab
3. Run *az account show* to verify you have logged in successfully
4. Register the provider using Azure CLI:
az provider register --namespace Microsoft.ContainerInstance
5. Verify registration
az provider show --namespace Microsoft.ContainerInstance --query "registrationState"

b. Run the terraform command to execute
terraform init
terraform fmt
terraform validate
terraform apply






