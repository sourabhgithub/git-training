# TAS JIRA API
![Quality Gate Status](http://100.105.82.201:9000/api/project_badges/measure?project=com.asurion.gtcoe%3Agtcoe-jira&metric=alert_status)

[![Build Status](http://100.105.78.216:8080/buildStatus/icon?job=GTCOE_CORE)](http://100.105.78.216:8080/job/GTCOE_JIRA/)

## Getting Started
## Developing

To develop this application, you will need Spring-Boot and Java 8. 

You can run this project locally using the [Spring Boot Maven Plugin][]. 

[Spring Boot Maven Plugin]: https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html
[Spring Boot Developer Tools]: https://docs.spring.io/spring-boot/docs/current/reference/html/using-boot-devtools.html

### Running the application

To run the application, execute the following Maven goal:

On Windows, make sure to point to the correct file based on the version number:

```test
mvn clean install && mvn spring-boot:run
```

On Mac or Linux:

```
mvn clean install && mvn spring-boot:run
```

##### Running the Docker Container

Below command will package and run the application on container

```
mvn docker:build
docker run -it -p 9999:8080 tas-jira
```