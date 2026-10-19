# Lab 4: Docker Debug

Starting code for **Lab 4** of the course *Containers & Orchestration* (Howest MCT, 2026-2027).
The assignment itself is on Leho: 🟢 Praktijk, Lab 4.

A colleague tried to prepare this to-do application for Docker, and the attempt has not fully succeeded.
Your job is to find and fix the problems, and then to improve the setup.

## What is in this repository

| Path | Contents |
|---|---|
| `compose.yaml` | The services: PostgreSQL, the backend and the frontend. |
| `backend/` | FastAPI backend that stores the to-dos in PostgreSQL. |
| `frontend/` | Flask frontend that talks to the backend. |

## Before you start

- You do not need to change any Python code.
- Log in to Docker Hub once with `docker login`. Anonymous pulls are limited per IP address, and everyone in the classroom shares one address.
- Commit along the way, not only at the end: your commit history shows how you solved each problem.
