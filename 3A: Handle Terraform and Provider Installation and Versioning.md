Terraform 
- [watch this video to install on Windows](https://www.youtube.com/watch?v=R3fohgDHCYg)
- Written in Golang 
- executable comes in a zip file 

Providers 
- "executable plug in that contains the code neccesary to interact with the api of the service" 
- eg to work with Azure you will need the Azure Provider
- Azure provider can be supplied through env variable or cached creds. 
- avoid hard coding 
- version -> constrain provider to specific version 
- 

provider azurerm {
  version - "=1.41.0"
  tenant_id = var.tenant.id
  subscription = var.subscription_id
}

