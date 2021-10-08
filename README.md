# spring-boot-demo
Spring Boot DEMO

## USED TUTORIAL 
https://www.youtube.com/watch?v=vtPkZShrvXQ
* Spring Boot Tutorial for Beginners (Java Framework)
* 1h49m28s, 03.09.2019

## USED PROJECT
https://start.spring.io
* Maven Project
* Spring Boot 2.5.5
* jar Packaging
* Java 11 (jdk-11.0.12+7)
* Dependencies: 
  * Spring Web
  * Build web, including RESTful, applications using Spring MVC. Uses Apache Tomcat as the default embedded container.

## JSON EXAMPLES
`GET localhost:8080/api/v1/person` 
### INPUT
```
{
    "name": "Vorname Nachname"
}
``` 
### OUTPUT
```
[
    {
        "id": "caab35ed-db3b-4513-a54f-8ff8ed36e948",
        "name": "Vorname Nachname"
    }
]
``` 