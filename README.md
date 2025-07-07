# DevOps Flask Application

This is a simple Flask web application designed to demonstrate a basic DevOps deployment pipeline using Docker and Kubernetes.

## Project Structure

- `app.py`: A minimal Flask application that returns a greeting message.
- `requirements.txt`: Python dependencies (`flask` and `gunicorn`).
- `Dockerfile`: Defines the Docker image for the Flask application.
- `deployment.yaml`: Kubernetes Deployment manifest to deploy the Flask app.
- `service.yaml`: Kubernetes Service manifest to expose the Flask app.

## Application Details

The Flask app listens on port 5000 and responds with the text:
Hello from DevOps
## Prerequisites

- Docker is installed and running
- Kubernetes cluster access (e.g., Minikube, kind, or cloud provider)
- `kubectl` CLI configured to access your cluster

## How to Build and Run

### Locally with Docker

1. Build the Docker image:

```bash
docker build -t devops-flask-app.
