# Docker Setup for Educore

This directory contains the Docker Compose configurations for running Educore in development and production environments.

## Development

To run the application with hot reloading:

```bash
docker compose -f docker/docker-compose.dev.yml up --build
```

## Production

To run the production build:

```bash
docker compose -f docker/docker-compose.yml up -d --build
```

To stop containers:

```bash
docker compose -f docker/docker-compose.yml down
```
