# 🐳 Docker Mastery Roadmap — `docker-basics`

This document outlines a comprehensive learning path to master Docker, from beginner fundamentals to advanced real-world usage. This file is specific to the `docker-basics` branch and is designed to guide your progress.

---

## 🧱 Phase 1: Foundations — Understand Core Docker Concepts

### ✅ Key Topics
- What is Docker and why use it?
- Installing Docker (Docker Desktop / CLI)
- Containers vs VMs
- Docker architecture: Engine, Daemon, CLI, Images, Containers

### ✅ Hands-on Tasks
- Install Docker on your OS
- Run basic containers:
  ```bash
  docker run hello-world
  docker run -it ubuntu /bin/bash
  ```
- Learn CLI commands: `run`, `ps`, `exec`, `stop`, `rm`, `images`, `logs`, `inspect`

---

## 🛠️ Phase 2: Building Images — Dockerfiles & Custom Containers

### ✅ Key Topics
- Dockerfile syntax: `FROM`, `RUN`, `COPY`, `WORKDIR`, `CMD`, `ENTRYPOINT`, `ENV`
- Layered architecture of images
- Multi-stage builds
- Using `.dockerignore`

### ✅ Practice
- Dockerize:
  - Node.js API
  - Python Flask app
  - Static HTML app

### ✅ Files
- `Dockerfile`
- `.dockerignore`

---

## 🧪 Phase 3: Volumes, Networks & Environment

### ✅ Key Topics
- Volumes: named, anonymous, bind mounts
- Docker networks: bridge, host, overlay
- Environment variables and `.env` files

### ✅ Practice
- Persist database data with volumes
- Create custom Docker networks
- Use `.env` files with containers

---

## 🧰 Phase 4: Docker Compose — Multi-Container Applications

### ✅ Key Topics
- `docker-compose.yml` syntax
- Services, networks, volumes, environment
- Linking backend & frontend containers

### ✅ Projects
- Node.js + MongoDB
- Vue + Express + PostgreSQL

### ✅ Files
- `docker-compose.yml`
- `.env`

---

## ⚙️ Phase 5: Image Management & Optimization

### ✅ Key Topics
- Image tagging, pushing, pulling
- Layer caching & optimization
- Clean-up: `docker system prune`, `image rm`, `container rm`

### ✅ Practice
- Push/pull from DockerHub
- Optimize builds using caching, `.dockerignore`, and `--target`

---

## 🛡️ Phase 6: Security & Best Practices

### ✅ Key Topics
- Docker Bench for Security
- Run as non-root user
- Scan for vulnerabilities

### ✅ Tools
- `docker scan`
- `trivy`
- Secrets management

---

## 📦 Phase 7: Real-World CI/CD & Production

### ✅ Key Topics
- Healthchecks
- CI/CD pipelines (GitHub Actions)
- Docker in production environments

### ✅ Practice
- Dockerize and deploy a full-stack app
- Use GitHub Actions to build & push Docker images

---

## ☸️ Phase 8: Docker Orchestration (Bonus)

### ✅ Topics
- Docker Swarm basics
- Services, stacks, secrets, rolling updates
- Scaling containers

---

## 🧠 Bonus: Dev Environment Optimization

- Use CLI aliases
- VSCode Docker Extension
- Docker context for remote machines

---

## 📚 Recommended Resources

- Official Docs: https://docs.docker.com/
- YouTube: TechWorld with Nana, Bret Fisher
- Book: Docker Deep Dive by Nigel Poulton
- Playground: https://labs.play-with-docker.com/

---

## ✅ Suggested Repo Folder Layout

```
docker-basics/
├── hello-world/
├── dockerfile-node/
├── volumes-demo/
├── networks-demo/
├── docker-compose-labs/
├── optimization/
├── security/
├── swarm/
```

Happy learning! 🚀