# microservices-example-service-discovery
The project implements the microservices architecture Service Discovery example that provides the service registry for the two sample micro services: User Service and Message Service.

# Details

This project provides the Eureka service registry for the two sample micro services: User Service and Message Service.

Before running these two micro services, make sure you run this micro service so that User Service and Message Service could register in this service registry. 

# How to Build and Run

1. Open up a terminal and use the following command: **mvn spring-boot:run**
2. The micro service which is our service registry will run on port 1111, as specified in application.yml
3. To see whether other micro services have registered successfully, visit [http://localhost:1111](http://localhost:1111])