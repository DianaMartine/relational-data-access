# Accessing Relational Data using JDBC with Spring

Creating a relational data access with <strong><em>spring-boot-initializr</em></strong>


You will build an application that uses Spring’s ```JdbcTemplate``` to access data stored in a relational database.

### The response message is:

``` 
2019-09-26 13:46:58.561  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Creating tables
2019-09-26 13:46:58.564  INFO 47569 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2019-09-26 13:46:58.708  INFO 47569 --- [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2019-09-26 13:46:58.809  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for John Woo
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Jeff Dean
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Josh Bloch
2019-09-26 13:46:58.810  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Inserting customer record for Josh Long
2019-09-26 13:46:58.825  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Querying for customer records where first_name = 'Josh':
2019-09-26 13:46:58.835  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Customer[id=3, firstName='Josh', lastName='Bloch']
2019-09-26 13:46:58.835  INFO 47569 --- [           main] c.e.r.RelationalDataAccessApplication    : Customer[id=4, firstName='Josh', lastName='Long']
```


## What You Need
- About 15 minutes
- A favorite text editor or IDE
- <a href="http://www.oracle.com/technetwork/java/javase/downloads/index.html">JDK 1.8</a> or later
- <a href="http://www.gradle.org/downloads">Gradle 4+</a> or <a href="https://maven.apache.org/download.cgi">Maven 3.2+</a>


## See you soon

- 🤝 Fork this repo for study and contribute it.
- ⭐ Leave your star in this repo