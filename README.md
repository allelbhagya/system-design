## System Design Notes

Welcome to the System Design Notes repository! This repository serves as a collection of notes on system design, capturing concepts, principles, and best practices.

## Topics covered

### lesson -1

- introduction to system design
- horizontal and vertical scaling
- terminology and steps

### lesson -2

- load balancing
- consistent hashing
- message queue

### resources

https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX
interview - https://www.youtube.com/channel/UC9vLsnF6QPYuH51njmIooCQ
https://www.hiredintech.com/classrooms/system-design/lesson/52
https://github.com/donnemartin/system-design-primer

### intro

1. Scalability: Every system we use today is built to scale. Scalability is a system’s ability to perform under load. Understand the different approaches to cope with the load — Horizontal Scaling and Vertical Scaling.
2. Caching: With increasing load, there is an increase in data and fetching from the database every time results in a slow response. Caching improves page load times and can reduce the load on your servers and databases. Read through the caching mechanisms and understand different caching strategies.
3. Databases: Understand different storages, Relational Databases, and Non-Relational Databases, and SQL vs. NoSQL. For SQL, go through topics like replication, sharding, functional partitioning, denormalization, and ACID properties. For NoSQL, understand topics like BASE properties, different ways NoSQL data is stored — key-value store, document store, wide column store, or a graph database.
4. Load Balancers: When there is an increasing load, we often use load balancers to distribute the load between the resources such as application servers and databases. Understand the different uses of load balancers and the different load balancing strategies available.
5. Microservices: Microservice architecture is an application that is deployed as a collection of lightweight and small services. Each service is independent of others and communicates through a well-defined mechanism. While you’re here, read Monolithic vs. Microservice architecture and Service Registry and Discovery.
6. Other topics worth reading and learning are — Consistency Patterns, Availability Patterns, CAP theorem, Asynchronous communication mechanisms, long polling, rate limiting, consistent hashing, and Reverse Proxy.
