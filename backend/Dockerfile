# Parent image runtime
FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/Kefele.jar app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]