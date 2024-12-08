# Use OpenJDK as base image
FROM openjdk:11-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Java application
COPY target/KubernetesDockerApp.jar /app/KubernetesDockerApp.jar

# Command to run the application
CMD ["java", "-jar", "KubernetesDockerApp.jar"]
