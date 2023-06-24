# Spring Boot Minio Example
>**MinIO example with Spring Boot application**

>**For about [MinIO](https://min.io/)**

<p align="center">
<img src="https://github.com/NrktSLL/spring-boot-minio/blob/master/images/minio.png" alt="Spring Boot Minio" width="40%" height="40%"/> 
</p>

## Prerequisites

*  Docker
*  Docker Compose

## Installation
>Container creation with [Buildpacks](https://buildpacks.io/) 
```
mvn clean install && docker-compose up -d
```

## Used Dependencies
* Spring Boot Hateoas
* Spring Boot Actuator
* Spring Boot Web
* Sringdoc OpenApi (openapi-ui + openapi-hateoas)
* Jlefebure Minio
* Mapstruct
* Lombok
* Jackson Dataformat Xml

## Abilities
* Content Negotiation Support(Json,Xml,Hal Support)
* MinIO Storage

## Swagger
> **Access : http://localhost:8080/api/documentation/**


<img src="https://github.com/NrktSLL/spring-boot-minio/blob/master/images/minio-swagger.png" alt="Spring Boot Minio Swagger" width="100%" height="100%"/> 

## MinIO Browser
> **Access : http://localhost:9000/**


<img src="https://github.com/NrktSLL/spring-boot-minio/blob/master/images/minio-browser.png" alt="Spring Boot Minio Swagger" width="100%" height="100%"/> 


## Resource
* https://medium.com/@kaoxyd/minio-and-spring-boot-with-minio-starter-d7efcce5f99a
* https://github.com/jlefebure/spring-boot-starter-minio
* https://docs.min.io/

