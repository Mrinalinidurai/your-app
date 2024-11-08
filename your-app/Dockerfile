# Use a base image with Java 17
FROM openjdk:17-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the JAR file from the target directory to the container
COPY target/your-app-1.0-SNAPSHOT.jar your-app.jar

# Expose the port your app will run on
EXPOSE 8080

# Run the application
CMD ["java", "-jar", "your-app.jar"]

