# Domain Driven Design - Lab

This project contains the backend for an e-commerce website.
At the moment it only contains a product catalog. 

## Domain Model

Each _Product_ in the catalog has a _name_ and a unique identifier _Sku_. 

### Entities

- Product

### Value Objects

- Sku

## Project Structure

The structure of the source code is based on the DDD layers: 

- **API**: Entry-point for incoming user requests.
- **Application**: Orchestration layer, translates API objects <-> Domain models.
- **Domain**: Entities, Value Objects and all the business logic goes here.
- **Infrastructure**: Interacts with low level external services like databases.




