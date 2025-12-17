# Jenkins CI/CD Pipeline for Dockerized Flask Application

This project demonstrates a complete CI/CD pipeline using **Jenkins**, **Docker**, and **Docker Hub** for a simple **Flask** web application.  
Whenever the pipeline runs, Jenkins automatically clones the repository, builds a Docker image, and pushes it to Docker Hub.

---

## Project Overview

- Flask-based Python web application
- Dockerized using a lightweight Python image
- Jenkins pipeline for Continuous Integration and Deployment
- Docker image pushed to Docker Hub automatically

---

##  Technologies Used

- **Python 3.9**
- **Flask 3.0**
- **Docker**
- **Jenkins (Declarative Pipeline)**
- **Docker Hub**

---
## Project Structure

jenkins_ci/
├── Dockerfile          # Defines the Docker image for the Flask application
├── Jenkinsfile         # Jenkins declarative pipeline for CI/CD automation
├── app.py              # Flask application source code
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation

