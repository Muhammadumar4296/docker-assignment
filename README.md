<<<<<<< HEAD
This repository contains two containerized projects:

Projects
Next.js Docker - Next.js application running in Docker container
FastAPI Docker - FastAPI application running in Docker container
How to Run
Next.js:
cd nextjs-docker
docker build -t nextjs-docker-app .
docker run -d -p 3000:3000 nextjs-docker-app
Access: http://localhost:3000

FastAPI:
cd fastapi-docker
docker build -t fastapi-docker-app .
docker run -d -p 8000:8000 fastapi-docker-app
Access: http://localhost:8000

Screenshots
Docker Desktop screenshots are included showing both containers running.
=======
# Docker Assignment

This repository contains two containerized projects:

## Projects
1. **Next.js Docker** - Next.js application running in Docker container
2. **FastAPI Docker** - FastAPI application running in Docker container

## How to Run

### Next.js:
```bash
cd nextjs-docker
docker build -t nextjs-docker-app .
docker run -d -p 3000:3000 nextjs-docker-app
```
Access: http://localhost:3000

### FastAPI:
```bash
cd fastapi-docker
docker build -t fastapi-docker-app .
docker run -d -p 8000:8000 fastapi-docker-app
```
Access: http://localhost:8000

## Screenshots
Docker Desktop screenshots are included showing both containers running.
>>>>>>> 02bfa94ef38ed6e22ec5a35fd4006c0914566662
