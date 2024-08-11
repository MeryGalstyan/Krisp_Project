# Krisp_Project

# Recommendation System

This project is a simple recommendation system with two services: Generator and Invoker, using Redis for caching. Each service is packaged as a Docker container.

## Services

1. **Generator**: Generates random recommendations based on model name and viewer ID.
2. **Invoker**: Returns recommendations, using a cascade method and caching results.

## Setup and Deployment

### Prerequisites

- Docker
- Docker Compose

### Steps

1. Build and run the services using Docker Compose:
   ```bash
   docker-compose up --build
