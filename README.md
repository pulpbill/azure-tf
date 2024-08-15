# azure-tf
Azure Terraform tests

# Install Azure CLI
https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-linux 

Check azure cli version:
`az version`

# Working with Azure CLI

Make sure you're logged in and, working with the desired account/tenant and subscription: 
* https://learn.microsoft.com/en-us/cli/azure/authenticate-azure-cli

`az login`

`az account show`

`az account set --subscription <your-subscription-id>`

* Don't mix up account/subscription/tenant/user and resource groups: https://learn.microsoft.com/en-us/cli/azure/manage-azure-subscriptions-azure-cli

* You could define your resource group at provider.tf but we're gonna declare it at main.tf

# Install Terraform
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli

Check tf version:
`terraform version`

