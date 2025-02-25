# Use the base image for creating the java environment
FROM openjdk:17-jdk-alpine

# set up the working directory of the container
WORKDIR /app

# Copy all the files from current directory to the container work directory
COPY src/Main.java /app/Main.java

# Run the command to compile the java application
RUN javac Main.java

# Enter the command to run the final command
CMD ["java","Main"]