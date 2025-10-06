# Dockerize-a-Simple-Web-App

## Project Description
A simple Python Flask application containerized using Docker for easy deployment and portability.

## Features
- Python Flask application  
- Docker containerization  
- Optional CI workflow integration

## Prerequisites
- Python 3.x  
- Docker installed  
- Git & GitHub account  

## Installation Commands

# Install Python & pip
sudo apt update
sudo apt install python3 python3-pip -y

# Install Docker
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
docker --version

# Build Docker image
docker build -t flask-app .

# Run Docker container
docker run -d -p 5000:5000 flask-app

## Connectivity Commands
# Access the app in browser
http://localhost:5000

# Stop container
docker ps
docker stop <container-id>

## How to Run / Access
http://localhost:5000
