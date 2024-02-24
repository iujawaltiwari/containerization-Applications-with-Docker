# Get a base image with JDK installed 

FROM openjdk:11

# Create a working directory to compile, run java apps

WORKDIR /app

# Copy code from local machine docker container

COPY Hello.java .

# Compile the code 

RUN javac Hello.java

#Run the java app

CMD ["java","Hello"]
