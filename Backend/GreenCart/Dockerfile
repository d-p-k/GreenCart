# Use lightweight Java runtime
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy jar file (change name if needed)
COPY target/*.jar greencart.jar

# Expose port (Render uses 10000 by default, but Spring uses 8080)
EXPOSE 8080

# Run the app
ENTRYPOINT ["java", "-jar", "greencart.jar"]