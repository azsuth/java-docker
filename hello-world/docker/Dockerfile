FROM openjdk:8-jre-alpine

EXPOSE 5000:8080

COPY hello-world-0.0.1-SNAPSHOT.jar /app.war

CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/app.war"]