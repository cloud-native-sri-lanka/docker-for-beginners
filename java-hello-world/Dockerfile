# Use a base image with Java pre-installed
FROM openjdk:8-jdk-alpine

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy the compiled Java class file into the container
COPY HelloWorld.java .

# Compile the Java program
RUN javac HelloWorld.java

# Command to run the Java program
CMD ["java", "HelloWorld"]
