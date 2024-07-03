# Base image
FROM openjdk:11-jre-slim

# Set working directory
WORKDIR /app

# Copy the packaged jar file into the container
COPY target/my-app.jar /app

# Specify the command to run your application
CMD ["java", "-jar", "my-app.jar"]
