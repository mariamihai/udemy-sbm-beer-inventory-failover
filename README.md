Docker [![Docker](https://img.shields.io/docker/v/mariamihai/sbm-beer-inventory-failover?sort=semver)](https://img.shields.io/docker/v/mariamihai/sbm-beer-inventory-failover?sort=semver)

# SBM Beer Inventory Failover Service
Spring Boot Microservice project

## Description
Failover project for the [Beer Inventory Service](https://github.com/mariamihai/udemy-sbm-beer-inventory-service)

Overview of the project [here](https://github.com/mariamihai/udemy-sbm-overview).

## API Version
Version was not added to the current project as the project contains only one endpoint with no parameters.

## Implementation Details
### Properties
```
spring.application.name=beer-inventory-failover

server.port=8083
```

### API calls
#### Failover endpoint
* __URI:__ _/inventory-failover_

 * __Method:__ _GET_

 * __URL params:__ <br/>
    * required: - <br/>
    * optional: -
    
 * __Success response:__
    * Code: 200 <br/>
    * Content: (TODO - response will be added)
    
       ``` 
       
       ```