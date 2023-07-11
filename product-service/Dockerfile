# Use an OpenJDK base image
FROM openjdk:17-jdk

# Set the working directory inside the container
WORKDIR /app

# Copy the compiled Spring application JAR file to the container
COPY target/your-application.jar app.jar

# Expose the port on which your Spring application runs
EXPOSE 8080

# Set the entrypoint command to run the Spring application
ENTRYPOINT ["java", "-jar", "app.jar"]
