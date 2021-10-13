   
# List API's:
## List of Pets (GET)
http://claimprocesswebapp.azurewebsites.net/pets


## GET By ID
http://claimprocesswebapp.azurewebsites.net/pets/2c861330-2bd7-11ec-a979-cd62afb3ff8b



## POST Pets Info :
http://claimprocesswebapp.azurewebsites.net/pets


## Input Request (JSON)
{​​​​​​"name":"springpet","species":"dogs"}​​​​​​


## Response:
Added Pet{​​​​​​id=fa251850-2bdb-11ec-8672-731eb1a7bd72, name='springpet', species='dogs'
}​​​​​​

# Flow is Like this : 
  Azure App Service  ---> Spring BOOT APP ---> Azure Cosmos DB(Cassandra DB) 
