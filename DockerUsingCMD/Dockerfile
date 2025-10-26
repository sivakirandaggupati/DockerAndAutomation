# Use a base image with Java installed
FROM openjdk:21

# Set the working directory inside the container
WORKDIR /app/

# Copy the compiled JAR file into the container
# Replace 'your-application.jar' with the actual name of your JAR
COPY src /app/

# Expose the port your application listens on (if it's a web application)
# For example, if your application runs on port 8080
#EXPOSE 8080

# Command to run the Java application
CMD ["java", "Test"]