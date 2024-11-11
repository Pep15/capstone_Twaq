# Capstone Twaq

## Overview
This project focuses on containerizing and running the web application using **Docker** and **Docker Compose**. The focus was on setting up a reliable and efficient environment to run the pre-built application in containers.

## Key Features:
- **Dockerization:** A **Dockerfile** was created to containerize the application, making it portable and easy to deploy in various environments.
- **Multi-Container Setup:** **Docker Compose** was used to orchestrate multiple containers, such as the web application and any associated services like databases or caches (if needed).
- **Environment Configuration:** Docker Compose files were configured with environment variables to ensure seamless integration and proper container communication.

## Technologies Used:
- **Docker** for containerization
- **Docker Compose** for managing multi-container environments
- Web Application: A pre-built application, containerized and run in Docker

## GitHub Workflow:
The project utilizes **GitHub Actions** to automate essential DevOps tasks:
- **Automated Testing:** Ensuring that changes to the Docker setup or other configurations are validated before deployment.
- **Continuous Deployment:** Using GitHub Actions to trigger the automated deployment process, ensuring the latest version of the application is containerized and deployed smoothly.

![Tuwaiq Academy Logo](./images/logo-h.png)
