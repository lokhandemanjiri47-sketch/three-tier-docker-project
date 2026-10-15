# three-tier-docker-project
Three-Tier Django Notes Application using Docker, Docker Compose, Nginx, Django, and MySQL. Deployed as a multi-container application with separate Web, Application, and Database tiers. Includes Docker networking, container management, and application verification.
# Three-Tier Django Notes Application Using Docker

## Project Overview
This project demonstrates a three-tier web application using Docker and Docker Compose. The application is built using Django and uses MySQL as the database.

## Architecture
The project consists of three tiers:

1. **Web Tier:** Nginx handles HTTP requests and acts as a reverse proxy.
2. **Application Tier:** Django handles application logic.
3. **Database Tier:** MySQL stores application data.

## Technologies Used
- Docker
- Docker Compose
- Nginx
- Django
- Python
- MySQL
- Git and GitHub

## Project Setup

### 1. Clone the Repository
```bash
git clone https://github.com/thawaresameer715-cyber/django-notes-app.git
cd django-notes-app
```

### 2. Start the Application
Check the Dockerfile, docker-compose.yml, and required environment configuration before running:

```bash
docker-compose up -d
```

### 3. Verify Containers
```bash
docker ps -a
docker-compose logs --tail=50
```

## Key Learnings
- Docker containerization
- Multi-container application deployment
- Docker Compose
- Container networking
- Application troubleshooting

## Project Objective
To understand how the web, application, and database tiers work together using Docker containers.

## Credits
Original application source code: [django-notes-app](https://github.com/thawaresameer715-cyber/django-notes-app)

This repository is based on the referenced source project.
