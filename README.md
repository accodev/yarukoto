# Yarukoto

## Introduction

This project consists of two main services: `backend` and `frontend`. Both services can be spun up using Docker Compose.

## Prerequisites

- Docker
- Docker Compose

## How to Spin Up the Application

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yarukoto.git
    cd yarukoto
    git submodule init
    git submodule update
    ```

2. Build and start the services using Docker Compose:
    ```sh
    docker-compose up --build -d
    ```

3. Access the services:
    - Backend: `http://localhost:5277` (there's no `/` endpoint, access it via API calls)
    - Frontend: `http://localhost:3000` (this is the frontend, enjoy)

## Stopping the Application

To stop the application, run:
```sh
docker-compose down
```

## Additional Information

- The backend service (`backend`) exposes port 5277.
- The frontend service (`frontend`) exposes port 3000.