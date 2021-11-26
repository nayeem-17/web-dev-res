## Requirements
- Java
- Object Oriented Programming
- Basic Knowledge of Build Tool (Maven or Gradle)

## Websites

- Create Project [Spring Initalizr](https://start.spring.io/) or [IntelliJ Idea](https://www.youtube.com/watch?v=5kOGdZmpSDI)
- For Spring related issues or tutorial, first preference [Baeldung](https://www.baeldung.com/) then others

## Tutorials

- Best Tutorials for Starters [Spring Tutorial](https://www.baeldung.com/spring-tutorial)
- Start with [Spring Boot Quick Start](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTbx8p2oCgcAQGQyqN8XeA1x)
- ~~Spring Security [AmigosCode](https://www.youtube.com/watch?v=her_7pa0vrg)~~
- Best security tutorial is from Laurentiu spilca(https://www.youtube.com/playlist?list=PLEocw3gLFc8XRaRBZkhBEZ_R3tmvfkWZz) 
  **Warning: Spring security is a very complex and robust security framework. You may get lost completely in spring security. Better not start with security for beginners ***

## Need to Know

- You can use Spring Boot as only REST API backend or fullstack frontEnd with JSP.
- For using only as backend, you need to know how to configure Jackson (JSON De/Serializer), Security and CROS
- Spring Has diffrent Modules - Core, Security, Data, Web
- ~~You can not use Spring JPA Hibernate for CSE215 course, use JDBC~~
- You can indeed use spring data jpa. There is options for native query to database.

## Basic project structure of a spring boot project:

  Project dir</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Controller</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Sevice</br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Service interface</br>
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Service implementation</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Repository</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Utils</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Config</br>
    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Security</br>
