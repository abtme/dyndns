# Use the official Python image
FROM python:latest

# Set the working directory in the container
WORKDIR /app

# Copy the script into the container
COPY script.py .
COPY requirements.txt .

# Install any needed dependencies specified in requirements.txt
RUN pip install --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt

# Run script.py when the container launches
CMD ["python", "./script.py"]
