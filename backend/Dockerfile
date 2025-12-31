# Use official OpenJDK image
FROM eclipse-temurin:17-jdk

# Set working directory
WORKDIR /app

# Copy the built JAR file
COPY target/*.jar app.jar

# Expose backend port
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "app.jar"]

