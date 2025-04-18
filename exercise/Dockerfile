# Use the base image
FROM ubuntu:24.04

# Update and install curl and bash
RUN apt-get update && apt-get install -y curl bash

# Set working directory
WORKDIR /usr/src/app

# Copy script into the image
COPY script.sh .

# Make sure the script is executable
RUN chmod +x script.sh

# Set the command to run on container start
CMD ./script.sh
