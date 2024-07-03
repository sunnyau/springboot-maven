# java-springboot
Spring boot built by maven

It has been upgraded to Java 21

The codes are initially copied from https://github.com/spring-guides/gs-spring-boot/tree/main/complete


# To start a spring boot application

mvn spring-boot:run

# To check spring boot result

http://localhost:8080/

# To connect to H2 database

http://localhost:8080/h2-console

If you see this error

> Database "/home/sunny/test" not found, either pre-create it or allow remote database creation (not recommended in secure environments) [90149-224] 90149/90149 (Help)

You need to create an empty file call test.mv.db

> sunny@TDesktop:~$ touch test.mv.db

> sunny@TDesktop:~$ chmod 777 test.mv.db

Afterwards you should be able to connect the H2 database.



## Reference

https://spring.io/guides/gs/spring-boot
https://www.baeldung.com/spring-boot-h2-database
