# CloudPulse

CloudPulse is a full-stack cloud monitoring and DevOps dashboard built to demonstrate hands-on experience with Docker, Jenkins CI/CD, Linux-based development, containerization, and deployment workflows.

The goal of this project is to simulate a real-world DevOps pipeline where a full-stack application is developed, containerized, tested, built, and deployed using industry-standard tools.

---

## Project Overview

CloudPulse is a web-based dashboard that allows users to monitor the health/status of different services. It includes a frontend interface, backend API, database, and a CI/CD pipeline powered by Jenkins.

This project focuses on:

- Full-stack application development
- Docker-based containerization
- Jenkins CI/CD automation
- Linux/WSL2-based development workflow
- Environment-based configuration
- Reverse proxy setup using Nginx
- Deployment to a VM or cloud-based environment

---

## Tech Stack

### Frontend
- React
- JavaScript / TypeScript
- HTML / CSS

### Backend
- Node.js / Express  
  <!-- Or replace with Python/Flask if we choose Python backend -->

### Database
- PostgreSQL / MySQL

### DevOps & Infrastructure
- Docker
- Docker Compose
- Jenkins
- Nginx
- GitHub
- WSL2 Ubuntu
- Docker Hub / Container Registry

---

## Planned Features

- User-friendly service monitoring dashboard
- Add and manage monitored services
- Display service status: Online, Offline, Warning
- Backend health-check API
- Database storage for services and status history
- Dockerized frontend, backend, and database
- Jenkins pipeline for automated build and deployment
- Nginx reverse proxy for production-style access
- Environment variable support for secure configuration

---

## Architecture

```text
User Browser
     |
     v
Nginx Reverse Proxy
     |
     |-------------------
     |                  |
     v                  v
React Frontend     Backend API
                        |
                        v
                   PostgreSQL/MySQL
