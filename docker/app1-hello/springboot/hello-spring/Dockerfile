FROM eclipse-temurin:21-jre
WORKDIR /app
COPY target/*.jar app.jar
EXPOSE 3000
CMD ["java", "-jar", "app.jar"]