
# Minecraft DevOps Platform

A hands-on DevOps learning project focused on
building, automating, and operating Minecraft
server infrastructure.

## Project Goals

- Learn Linux administration
- Deploy Minecraft using Docker
- Practice Git and GitHub
- Automate infrastructure with Ansible
- Learn Infrastructure as Code with Terraform
- Implement monitoring and backups
- Explore Kubernetes and CI/CD

## Current Architecture

Minecraft Java Client
        |
        | localhost:25565
        v
Docker Desktop (Windows)
        |
        v
Minecraft Paper Container
        |
        v
Docker Named Volume (Persistent Data)

## Technologies

- Docker and Docker Compose
- Minecraft Paper
- Git and GitHub

## Run Locally

Requirements:
- Docker Desktop
- Minecraft Java Edition

Start the server:

    docker compose up -d

Check status:

    docker compose ps

View logs:

    docker compose logs --tail 30

Stop and remove containers:

    docker compose down

Connect using:

    localhost:25565

## Roadmap

- [x] Local Minecraft Docker deployment
- [x] Docker health check
- [x] Git repository and GitHub
- [ ] Verify persistent storage recovery
- [ ] Ubuntu Linux deployment
- [ ] Ansible automation
- [ ] Terraform provisioning
- [ ] Monitoring and alerting
- [ ] CI/CD pipeline
- [ ] Kubernetes experimentation

## Notes

This is an educational infrastructure project.
Production deployment requires additional security,
backup, and operational considerations.
