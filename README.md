# Yarukoto Application

## Introduction

This project consists of two main services: `yarukoto-be` (backend) and `yarukoto-fe` (frontend). Both services can be spun up using Docker Compose.

## Prerequisites

- Docker
- Docker Compose

## How to Spin Up the Application

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yarukoto.git
    cd yarukoto
    ```

2. Build and start the services using Docker Compose:
    ```sh
    docker-compose up --build
    ```

3. Access the services:
    - Backend: `http://localhost:5277`
    - Frontend: `http://localhost:3000`

## Stopping the Application

To stop the application, run:
```sh
docker-compose down
```

## Additional Information

- The backend service (`yarukoto-be`) runs on port 5277.
- The frontend service (`yarukoto-fe`) runs on port 3000.