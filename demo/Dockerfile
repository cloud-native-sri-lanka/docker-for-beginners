# Use a base image with Java pre-installed
FROM maven:3.8.4-openjdk-17-slim 

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the source code into the container
COPY . .

# Build the application
RUN mvn clean install

# Expose the port that your Spring Boot application listens on
EXPOSE 8082

# Command to run the Spring Boot application
CMD ["java", "-jar", "target/demo-0.0.1-SNAPSHOT.jar"]
