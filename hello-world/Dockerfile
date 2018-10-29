FROM openjdk:8-jdk

EXPOSE 8080

COPY . /usr/hello-world

WORKDIR /usr/hello-world

RUN ./mvnw package

CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/usr/hello-world/target/hello-world-0.0.1-SNAPSHOT.jar"]