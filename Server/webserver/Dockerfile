FROM openjdk:11-jdk-slim

ARG JAR_FILE=build/libs/*.jar

COPY ${JAR_FILE} app.jar

EXPOSE 5000

ENTRYPOINT ["java", "-jar", "/app.jar"]