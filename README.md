# Flask CI/CD Deployment with Azure DevOps, Docker, ACR and AKS

## Project Overview

This project demonstrates a complete Continuous Integration and Continuous Deployment (CI/CD) workflow for a Python Flask application.

The Flask application was containerised using Docker, pushed to Azure Container Registry (ACR), deployed to Azure Kubernetes Service (AKS), and automated using Azure DevOps Pipelines.

The goal of this project is to move away from manual deployment and create an automated workflow where every code change pushed to the `main` branch can trigger a pipeline that builds, pushes, and deploys the latest application version.

---

## Objectives

The objectives of this assignment were to:

- Containerise a Python Flask application using Docker
- Push the Docker image to a private container registry
- Provision a Kubernetes cluster using Azure Kubernetes Service
- Create Kubernetes Deployment and Service manifests
- Expose the Flask application through a public IP address
- Store the project code in Azure Repos
- Create an Azure DevOps CI/CD pipeline
- Automatically build, push and deploy the application when code changes are committed
- Demonstrate Kubernetes scaling with multiple replicas
- Demonstrate how a failed pipeline prevents broken code from being deployed

---

## Technologies Used

| Tool / Platform | Purpose |
|---|---|
| Python Flask | Web application framework |
| Gunicorn | Production WSGI server for Flask |
| Docker | Containerisation |
| Azure Container Registry | Private container image registry |
| Azure Kubernetes Service | Managed Kubernetes cluster |
| Kubernetes | Container orchestration |
| Azure Repos | Source code repository |
| Azure DevOps Pipelines | CI/CD automation |
| Azure CLI | Azure resource management |
| kubectl | Kubernetes management |
| macOS Terminal | Local development environment |

---

## Project Structure

```text
flask-cicd-task/
├── flask_app.py
├── templates/
├── requirements.txt
├── Dockerfile
├── .dockerignore
├── .gitignore
├── deployment.yaml
├── service.yaml
├── azure-pipelines.yml
└── README.md