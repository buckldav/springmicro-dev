---
layout: default
title: Backend
parent: Technologies
nav_order: 1
---

# Backend

## Python

- [pytest](https://docs.pytest.org/en/7.2.x/) for testing.
- [FastAPI](https://fastapi.tiangolo.com/) for APIs.
  - [Uvicorn](https://www.uvicorn.org/) as the ASGI server.
  - [Beanie ODM](https://beanie-odm.dev/) with MongoDB (pymongo).
  - Example repo with JWT auth: [fastapi-beanie-jwt](https://github.com/flyinactor91/fastapi-beanie-jwt).
- [Django](https://www.djangoproject.com/) for monolith apps.
  - [PostgreSQL](https://www.postgresql.org/) for database.

## DevOps

Use [Docker](https://www.docker.com/), with Docker Desktop on Windows. Use [black](https://black.readthedocs.io/en/stable/) for formatting Python. Use [traefik](https://traefik.io/) as the load balancer/reverse proxy.
