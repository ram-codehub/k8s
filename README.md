# Hello World Kubernetes Deployment

This repository contains a simple "Hello World" app deployed on Kubernetes using Flask, Docker, and Helm.

## Steps to Deploy

1. Build and push the Docker image:
   ```bash
   docker build -t <your-dockerhub-username>/hello-world .
   docker push <your-dockerhub-username>/hello-world
Apply Kubernetes manifests:

bash
Copy code
kubectl apply -f k8s-manifests/
Access the app via the LoadBalancer IP.

yaml
Copy code

---

Let me know if you'd like help with Docker Hub setup, Kubernetes configurations, or running the deployment!