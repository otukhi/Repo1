# Use an official Python runtime as the base image.
FROM python:3.9

# Set the working directory within the container.
WORKDIR /usr/src/app

# Copy the Python script to the container.
COPY app.py .

# Define the command to run your Python script.
CMD [ "python", "app.py" ]
