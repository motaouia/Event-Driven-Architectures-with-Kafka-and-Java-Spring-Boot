Event-Driven Architectures with Kafka and Java Spring-Boot 
https://itnext.io/event-driven-architectures-with-kafka-and-java-spring-boot-revision-1-c0d43d103ee7



Introduction
Event-driven architectures have become the thing over the last years with Kafka being the de-facto standard when it comes to tooling.



We have a couple of building blocks, mainly
Infrastructure (Kafka, Zookeeper)
Producer (Java Spring-Boot Service)
Consumer (Java Spring-Boot Service)

Infrastructure
Only two components, despite the services, are needed to get an event-based architecture up-and-running: Kafka(is the “main”-part of handling the events) and Zookeeper.

ZooKeeper is a centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services.

