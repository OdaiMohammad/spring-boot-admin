![](./assets/logo-spring-boot-admin.png)

This community project provides an admin interface for [Spring Boot <sup>®</sup>](http://projects.spring.io/spring-boot/ "Official Spring-Boot website") applications.

Monitoring Python applications is available using [Pyctuator](https://github.com/SolarEdgeTech/pyctuator).

Spring Boot Admin provides the following features for registered applications:

* Show health status
* Show details, like
  * JVM & memory metrics
  * micrometer.io metrics
  * Datasource metrics
  * Cache metrics
* Show build-info number
* Follow and download logfile
* View jvm system- & environment-properties
* View Spring Boot Configuration Properties
* Support for Spring Cloud's postable /env- &/refresh-endpoint
* Easy loglevel management
* Interact with JMX-beans
* View thread dump
* View http-traces
* View auditevents
* View http-endpoints
* View scheduled tasks
* View and delete active sessions (using spring-session)
* View Flyway / Liquibase database migrations
* Download heapdump
* Notification on status change (via e-mail, Slack, Hipchat, ...)
* Event journal of status changes (non persistent)

## Quick start

Steps to run Spring Boot Admin in a development environment:
1. Make sure to [install Docker](https://docs.docker.com/get-docker/).
2. Start the Docker Engine.
3. Make sure to [install Docker Compose](https://docs.docker.com/compose/install/)
4. Simply use the run script to spin up Spring Boot Admin using the following command:
    ```bash
    ./run
    ```
5. Use the stop script to take Spring Boot Admin down using the following command:
    ```bash
    ./stop
    ```
For instructions on registering client applications see [The quick guide](http://codecentric.github.io/spring-boot-admin/2.3.1/#getting-started) to get started can be found in our docs.
