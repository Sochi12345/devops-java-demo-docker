# DevOps Java Demo (Dockerized)

## Overview

This is a **Dockerized Java Spring Boot application** connected to a **PostgreSQL database**.  
The project demonstrates building, containerizing, and running a Java application using **Docker** and **Docker Compose**, following professional DevOps practices.

---

## Features

- Java Spring Boot backend  
- PostgreSQL database integration  
- Dockerized application for easy deployment  
- Docker Compose orchestration for multi-container setup  
- Environment variables for configuration (no hard-coded secrets)  
- Volume mapping for persistent database storage  

---

## Technologies Used

- **Java 17** / Spring Boot  
- **PostgreSQL 15**  
- **Docker**  
- **Docker Compose**  
- **Git**  

---

## Getting Started

### Prerequisites

- Docker and Docker Compose installed on your machine  
- Git installed to clone the repository  

### Clone the Repository

```bash
git clone https://github.com/sochi12345/devops-java-demo-docker.git
cd devops-java-demo-docker

## How It Runs

This project uses Docker Compose to run:
- A Java application container
- A PostgreSQL database container

Configuration is handled via environment variables.
Containers are configured with automatic restart policies for reliability.