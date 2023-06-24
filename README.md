# MinIO-Java-Bliss

JavaMinIO: A beginner's guide to Java and MinIO integration. Learn how to leverage MinIO's object storage in Java applications with hands-on examples and step-by-step instructions.

## Minio

**Minio** allows the upload and download of files for containerized applications, respecting the interfaces of Amazon S3 solution. The Minio API is requested as HTTP, which allows interoperability regardless of the framework or language used.

In the article, I would use the following terms, which are specific to Minio or S3 :

- **Bucket**: Contains a set of files.
- **Prefix** : Virtually, this is a set of directories in which the file is located. All the files are arranged at the root of the bucket, and have a prefix of kind my/prefix/file.pdf.

## Used Dependencies

- Spring Boot Hateoas
- Spring Boot Actuator
- Spring Boot Web
- Sringdoc OpenApi (openapi-ui + openapi-hateoas)
- Jlefebure Minio
- Mapstruct
- Lombok
- Jackson Dataformat Xml

## Quick start

Go to this link :
https://min.io/docs/minio/windows/index.html
to know how to set up minio in your local machine

## Swagger

http://localhost:8080/api/documentation/

## MinIO Browser

http://localhost:9000/

## Ressource
You read this article : https://medium.com/@kaoxyd/minio-and-spring-boot-with-minio-starter-d7efcce5f99a
