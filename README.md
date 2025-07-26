# User Management API

Simple backend system for managing users built with FastAPI, SQLite, and Docker.

## Features
- Create, list, and retrieve users
- RESTful API
- Hashed passwords
- Dockerized

## Tech Stack
- Python 3.11
- FastAPI
- SQLite + SQLAlchemy
- Docker

## Getting Started

```bash
docker build -t user-api .
docker run -d -p 8000:8000 user-api
```

API docs: http://localhost:8000/docs

## Screenshots
![FastAPI Swagger UI](https://i.imgur.com/TwE4AgC.png)

## To Do
- [ ] JWT Authentication
- [ ] User update/delete
- [ ] Unit tests with Pytest

