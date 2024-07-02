# Ecommerce Microservices Service Discovery

This repository serves as the umbrella for the StatlerWaldorfCorp Ecommerce microservices demo.

The Catalog Service needs to provide information about products, including their availability or stock status.
To get the stock status of products, the Catalog Service queries the Inventory Service.

Dependency Relationship:

- The Catalog Service depends on the Inventory Service to fetch and display accurate inventory information to users.
This dependency is managed through HTTP calls made by the Catalog Service to the Inventory Service.

## System architecture

![Architecture](./System%20Architecture%20Service%20discovery.jpg)


## Microservices components

### 1. Catalog Service

The Catalog Service manages the product catalog for the ecommerce platform.

Repository: [EcommerceCatalog](https://github.com/pkErbynn/StatlerWaldorfCorp.EcommerceCatalog)

### 2. Inventory Service

The Inventory Service manages the product inventory for the ecommerce platform.

Repository: [EcommerceInventory](https://github.com/pkErbynn/StatlerWaldorfCorp.EcommerceInventory)
