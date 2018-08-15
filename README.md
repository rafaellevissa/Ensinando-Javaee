# Sistema AAC

## Run locally
The REST API requires [Java 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html) installed. To run it, `cd` to the `backend` directory and run the following command:
```
./mvnw spring-boot:run
```
Open the URL [http://localhost:8080](http://localhost:8080)

The web app requires Node.js and Angular CLI installed. To run it, `cd` to the `frontend` directory and run the following command:
```
ng serve
```
Open the URL [http://localhost:4200](http://localhost:4200)

## Run on server
```
sudo docker-compose up -d
```
> Docker and Docker Compose are required.

# Technologies
* [MySQL](https://www.mysql.com)
* [Java](https://www.oracle.com/br/java/index.html)
* [Apache Maven](https://maven.apache.org)
* [JDBC](https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc)
* [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/)
* [H2 Database Engine](http://www.h2database.com)
* [JPA](http://www.oracle.com/technetwork/java/javaee/tech/persistence-jsp-140049.html)
* [Project Lombok](https://projectlombok.org)
* [Spring Framework](https://spring.io)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Data JPA](https://projects.spring.io/spring-data-jpa)
* [Spring Data REST](https://projects.spring.io/spring-data-rest)

## DevOps tools
* [Git](https://git-scm.com)
* [GitLab](https://gitlab.com)
* [Docker](https://www.docker.com)
* [Jenkins](https://jenkins.io)
