 FROM eclipse-temurin:17-jdk-alpine

# Set workdir and copy the jar
WORKDIR /opt/app
ARG artifact=target/spring-boot-web.jar
COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]

