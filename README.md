Spring Boot 2 and Thymeleaf with Maven
======================================

- Spring Boot 
- Web application (WAR) packaging as well as self-contained JAR
- `Thymeleaf` with following dialects: Java 8 Time, Layout and Security
- `WebJars`

Prerequisites
-------------

- `JDK 11` and `JAVA_HOME` environment variable set 

Building the project
--------------------

Clone the repository:

    git clone https://github.com/kolorobot/spring-boot-thymeleaf

Navigate to the newly created folder:

    cd spring-boot-thymeleaf

Run the project with:

    ./mvnw clean spring-boot:run

Navigate to:

    http://localhost:8080

Login with: `user` and `demo`

Package the application
-----------------------

To package the project run:

    ./mvnw clean package



