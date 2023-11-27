# Spring Initializr
```
https://start.spring.io/#!type=maven-project&language=java&platformVersion=3.2.0&packaging=jar&jvmVersion=17&groupId=com.example&artifactId=springboot&name=springboot&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.springboot&dependencies=web,data-jpa,postgresql,validation
```
# API RESTful Spring Boot 3
- Spring Boot 3 e Java 17
- Spring Web MVC
- Spring Data JPA
- Spring Validation
- Spring Hateoas

# Requests
## POST
```
http://localhost:8080/products
```
## Json do POST
```
{
    "name": "nome do produto",
    "value": 0
}
```
____ 
## GET
```
http://localhost:8080/products
```
## GET Com id
```
http://localhost:8080/products/066ed68b-c7fc-4b26-bd39-14f2c8305fb2
```
## PUT com id 
```
http://localhost:8080/products/066ed68b-c7fc-4b26-bd39-14f2c8305fb2
```
## Json do PUT
```
{
  "name": "Pc Gamer Terabyte",
  "value": 7600.89
}
```
### DELETE com id
```
http://localhost:8080/products/066ed68b-c7fc-4b26-bd39-14f2c8305fb2
```
