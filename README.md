# Getting Started
Simple example demonstrating automatically created REST endpoints via spring-boot-starter-data-rest.
We also register the service to a Eureka instance, so make sure that Eureka is already running (http://localhost:8761/).
Implementation creates a REST service for a simple data class <Dog> without the need to write separate controller or any other service.

Navigate to http://localhost:8762/dogs to see the exposed dog microservice.
Navigate to http://localhost:8761/ on your computer to view the Eureka web console

### ToDo: Find solution for Eureka showing host.docker.internal instead of ip
- [spring-boot-cloud-eurka-windows-10-eurkea-returns-host-docker-internal-for-client](https://stackoverflow.com/questions/57319678/spring-boot-cloud-eurka-windows-10-eurkea-returns-host-docker-internal-for-clien)

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.3/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.3/maven-plugin/reference/html/#build-image)
* [Config Client Quick Start](https://docs.spring.io/spring-cloud-config/docs/current/reference/html/#_client_side_usage)
* [Eureka Server](https://docs.spring.io/spring-cloud-netflix/docs/current/reference/html/#spring-cloud-eureka-server)

### Guides
The following guides illustrate how to use some features concretely:

* [Service Registration and Discovery with Eureka and Spring Cloud](https://spring.io/guides/gs/service-registration-and-discovery/)

