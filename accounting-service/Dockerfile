FROM openjdk:11-jre-slim

WORKDIR /app

COPY target/accounting-service-1.0.0.jar app.jar

EXPOSE 8085

ENTRYPOINT ["java", "-jar", "app.jar"]