# Runtime stage
FROM openjdk:17-alpine
ADD target/ems-app.jar ems-app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/ems-app.jar"]