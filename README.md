# MinIO-Java-Bliss

JavaMinIO: A beginner's guide to Java and MinIO integration. Learn how to leverage MinIO's object storage in Java applications with hands-on examples and step-by-step instructions.

## Minio

**Minio** allows the upload and download of files for containerized applications, respecting the interfaces of Amazon S3 solution. The Minio API is requested as HTTP, which allows interoperability regardless of the framework or language used.

In the article, I would use the following terms, which are specific to Minio or S3 :

- **Bucket**: Contains a set of files.
- **Prefix** : Virtually, this is a set of directories in which the file is located. All the files are arranged at the root of the bucket, and have a prefix of kind my/prefix/file.pdf.

## Test

There is also a public instance to test on https://play.min.io/minio/. You can use the following credentials :

- Access Key : Q3AM3UQ867SPQQA43P2F
- Secret Key : zuf+tfteSlswRu7BJ86wekitnifILbZam1KYY3TG

## Quick start

Just add the dependency to an existing Spring Boot project.

```
<dependency>
    <groupId>com.jlefebure</groupId>
    <artifactId>spring-boot-starter-minio</artifactId>
    <version>1.1</version>
</dependency>
```

Then, add the following properties to your application.properties file.

```
# Minio Host
spring.minio.url=https://play.min.io
# Minio Bucket name for your application
spring.minio.bucket=00000qweqwe
# Minio access key (login)
spring.minio.access-key=###Your accessKey###
# Minio secret key (password)
spring.minio.secret-key=###Your secretKey###
```
