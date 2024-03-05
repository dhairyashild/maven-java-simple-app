# Use a base image with Java installed
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file into the container at /app
COPY /var/lib/jenkins/jobs/p1/builds/1/archive/target/my-app-1.0-SNAPSHOT.jar /app/your-application.jar

# Specify any necessary environment variables
# ENV ENV_VARIABLE_NAME=value

# Expose any necessary ports
 EXPOSE 9090

# Define the command to run your application
CMD ["java", "-jar", "your-application.jar"]
