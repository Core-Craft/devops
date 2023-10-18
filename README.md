# DevOps Directory

This directory contains the Docker configuration files for the project.

## Files

- `Dockerfile`: This file contains the instructions to build the Docker image for the backend application. It specifies the base image, working directory, dependencies to install, and the command to run the application.

- `docker-compose.yml`: This file is used to define and run multi-container Docker applications. It specifies the services, networks, and volumes for your application.

## Usage

To build and run the application using Docker Compose, navigate to this directory in your terminal and run:

```bash
docker-compose up --build
```

### Project structure is considered in following way:

```
project/
├── devops/
│   ├── Dockerfile
│   └── docker-compose.yml
└── backend/
    ├── app/
    │   └── main.py
    └── requirements/
        └── dev.txt

```

