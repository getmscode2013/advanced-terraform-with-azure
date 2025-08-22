### Advance Terraform  in Azure for Netwroking 

# Lab 1::
A. Login to Azure

In this objective. you will us the credetials provided by lab to log into Azure using the Azure credetials

1. Open terminal and run *az login* comman
2. In browser window that open, enter the credentails provided in lab
3. Run *az account show* to verify you have logged in successfully
4. Register the provider using Azure CLI:
az provider register --namespace Microsoft.ContainerInstance
5. Verify registration
az provider show --namespace Microsoft.ContainerInstance --query "registrationState"

# B. Run the terraform command to execute
terraform init
terraform fmt
terraform validate
terraform apply

# c. It will create the resouces as like below

<img width="1230" height="516" alt="image" src="https://github.com/user-attachments/assets/546a166a-0ebd-4d8d-bdec-c940bf477d70" />







