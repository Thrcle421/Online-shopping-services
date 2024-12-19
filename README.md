# Online Shopping Service
The online shopping service project is an e-commerce mall system developed based on the most popular microservice architecture. 

It uses Nacos to implement service governance, uses OpenFeign to implement remote calls and uses gateway to complete request routing and authentication.

It uses sentinel to complete microservice protection and uses Seata to complete distributed transactions.

## Split microservices

This project splits the online shopping service into 5 microservices:

- User service
- Product service
- Shopping cart service
- Transaction service
- Payment service
