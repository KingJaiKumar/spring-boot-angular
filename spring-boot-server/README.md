# Spring Boot MySQL Database CRUD example: Building Rest API with Spring Data JPA


## Run Spring Boot application
```
mvn spring-boot:run
```

## Using Docker build Spring Boot application
```
docker build -t spring-boot-jpa-mysql:1.0 .

## Using Docker run Spring Boot application
```
docker run -d --name spring-boot-jpa-mysql -p 8083:8081 spring-boot-jpa-mysql:latest
