# Containerization-Task

# Dockerized Fullstack Hello World
This repository demonstrates a simple Hello World application using Docker Compose to manage a multi-container setup, including a Flask application, an Nginx web server, and a PostgreSQL database.

## Prerequisites
Ensure you have the following installed on your system:

- Docker
- Docker Compose

## Directory Structure

dockerized-fullstack-hello-world
│   docker-compose.yml
│   README.md
│
└───app
│   │   Dockerfile
│   │   hello_world.py
│   │   requirements.txt
│   
└───webserver
│   │   Dockerfile
│   │   default.conf
│   
└───database
    │   Dockerfile


## Starting the Application
1. Build and start the containers using Docker Compose:
docker-compose up -d

## Stopping the Application
1. To stop the running containers, run the following command in the project directory:
docker-compose down
