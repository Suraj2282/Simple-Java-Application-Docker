
# Pull a base image from the central repository (docker Hub)
FROM openjdk:17-jdk-alpine

# Define a working directory
WORKDIR /app

# Copy whole files from the current project to the desired work app
COPY src/Main.java /app/Main.java

# Run the commands to compile the java application from Main.java file
RUN javac Main.java

# Run the final commands 
CMD ["java","Main"]

