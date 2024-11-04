FROM ubuntu:latest

# Update package lists
RUN apt-get update -y

# Install Git
RUN apt-get install -y git

# Create a directory for the repository
RUN mkdir /repo

# Set the working directory
WORKDIR /repo

# Initialize a Git repository
RUN git init