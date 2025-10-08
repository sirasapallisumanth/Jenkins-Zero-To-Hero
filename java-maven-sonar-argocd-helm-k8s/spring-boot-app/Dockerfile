# Base image with Maven + Java 17
FROM maven:3.9.9-eclipse-temurin-17

# Install Docker CLI
RUN apt-get update && \
    apt-get install -y docker.io && \
    apt-get clean

# Verify Docker version (optional)
RUN docker --version

