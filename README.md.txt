# Kubernetes Hello World

This is a simple Kubernetes project that deploys an Nginx web server with 2 replicas and exposes it via a NodePort service.

## Steps to Deploy
1. Apply the Deployment:
   ```bash
   kubectl apply -f deployment.yaml
   kubectl apply -f service.yaml
