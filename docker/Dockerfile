# Use an official Python runtime as a parent image
FROM python:3.7-slim

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install --trusted-host pypi.python.org -r requirements.txt

# Define environment variable
ENV TOKEN 1208543224:AAF-fgrmkVRII1a8phPm9i4S8e1kmrepIII
ENV CHATID -1001173845069
ENV DELAY 5

# Run app.py when the container launches
CMD ["python", "telegramrss.py"]
