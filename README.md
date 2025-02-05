# ordering-api-exercise

## Task
Warehouse needs a solution to see what orders are coming from store.
Build an API that receives customer orders, processes them asynchronously via a message queue worker, applies business logic, and stores the final processed orders in a database.

The API accepts an order with the following details:
```{
  "order_id": "12345",
  "customer_name": "John Doe",
  "items": [
    {"product_id": "A1", "quantity": 2, "price": 10.5},
    {"product_id": "B3", "quantity": 1, "price": 20.0}
  ]
}
```

# Requirements
## Functional
* As a user I can create new order
* As a user I can retrieve list of all orders
* As a user I can pay for the order

## Non-Functional
* System should be scalable. Meaning that multiple instances should process requests
* Include prerequisites and steps to launch in README
* The solution code must be in a git repository
* The API should be implemented using .NET Core framework (ideally the newest stable version)

## Bonus points stuff
* RESTful API
* Documentation generated from code (hint - Swagger)
* Automated tests
* Containerization/deployment (hint - Docker)
* Performance considerations
* Comments/thoughts on the decisions you made
