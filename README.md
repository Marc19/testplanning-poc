# Introduction
This is an implementation of a distributed system using .Net Core.

The business is quite simple. There are just 2 entities. The first is **Experiment** and the second is **Method**. An experiment can have 0 or many methods, and a method can have 0 or many experiments.

# Architecture
![alt text](./Assets/Architecture.png "Architecture")

# Technologies
* Domain-Driven Design
* Event Sourcing
* CQRS
* Saga Pattern (using [Chronicle](https://github.com/snatch-dev/Chronicle))
* [Kafka](https://kafka.apache.org/)

# Projects repositories
* [Experiments Microservice](https://github.com/Marc19/testplanning-poc-experiments)
* [Methods Microservice](https://github.com/Marc19/testplanning-poc-methods)
* [Saga Service](https://github.com/Marc19/testplanning-poc-saga)
* [Notification Server](https://github.com/Marc19/testplanning-poc-notifications)
* [Frontend](https://github.com/Marc19/testplanning-poc-ui)

# Documentation
Will be added soon...