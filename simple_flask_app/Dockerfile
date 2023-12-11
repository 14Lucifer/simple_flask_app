# Use an official Python runtime as a parent image
FROM ubuntu:20.04

# Set the working directory in the container to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install python3
RUN apt-get update
RUN apt-get install python3 -y

# Make port 9000 available to the world outside this container
EXPOSE 9000

# Run app.py when the container launches
CMD ["python3", "-m","http.server","9000"]

