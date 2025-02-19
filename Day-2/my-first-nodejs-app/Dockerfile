FROM ubuntu:latest

# Set the working directory in the image
WORKDIR /app

# Copy the source code from the host file system to image file system
COPY . /app

# Install the nodejs and necessory packages
RUN apt update && apt install -y nodejs npm

# Check the nodejs and npm version after installing nodejs and npm
RUN node -v && npm -v

# Run a command to start the application
CMD ["node", "hello.js"]


