# Docker Compose Flask App

Simple Flask app with Redis using Docker Compose.

## Run
```bash
docker compose up --build
Access

http://localhost:8000

Services
Flask (web)
Redis
Features
Counts visits using Redis
Notes
Flask app connects to Redis via service name (redis)
Defined using Docker Compose
