# Elliyani Portfolio Website

Personal portfolio website built with Flask and hosted on PythonAnywhere.

This website showcases my background, projects and ongoing transition into Cloud & DevOps engineering. It serves as a central place to document my learning journey, technical projects and hands-on experience with Python, Docker, Kubernetes, Azure and CI/CD workflows.

Live site: https://elliyani.pythonanywhere.com/

---

## About This Project

This portfolio was originally developed as part of my Flask learning journey and has since evolved into my personal website and project showcase.

The site is built using Python Flask with HTML templates and is maintained through a Git-based workflow using GitHub and PythonAnywhere.

Current sections include:

* About Me
* Technical background
* Cloud & DevOps learning journey
* Project showcase

---

## Technologies Used

| Tool / Technology | Purpose                        |
| ----------------- | ------------------------------ |
| Python            | Backend programming language   |
| Flask             | Web application framework      |
| HTML / CSS        | Frontend structure and styling |
| Git & GitHub      | Version control                |
| PythonAnywhere    | Hosting platform               |
| macOS Terminal    | Local development environment  |

---

## Local Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/elliopsys/flask-portfolio.git
cd flask-portfolio
```

### 2. Create a virtual environment

```bash
python3 -m venv venv
```

### 3. Activate the virtual environment

macOS / Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Flask application

```bash
flask --app flask_app run --port 5001
```

### 6. Open in browser

```text
http://127.0.0.1:5001
```

---

## Deployment Workflow

This portfolio follows a simple Git-based workflow:

```text
Local Development → GitHub → PythonAnywhere
```

### Typical update process

1. Edit and test locally
2. Commit and push changes to GitHub
3. Pull latest changes on PythonAnywhere
4. Reload the PythonAnywhere web app

---

## Featured Technical Project

### Flask CI/CD Deployment with Azure DevOps, Docker and Kubernetes

One of my featured projects involved building a complete CI/CD workflow for a Flask application using:

* Docker
* Azure Container Registry (ACR)
* Azure Kubernetes Service (AKS)
* Azure DevOps Pipelines
* Kubernetes manifests

The project automated the workflow from code commit to container deployment and included pipeline validation, scaling and deployment recovery demonstrations.

---

## Future Improvements

Planned improvements for this portfolio include:

* Dedicated project showcase pages
* Improved responsive design
* Blog/documentation section
* Dark mode support
* Automated deployment workflows
* Expanded DevOps project documentation

---

## Author

Elliyani
Aspiring Cloud & DevOps Engineer

GitHub: https://github.com/elliopsys
