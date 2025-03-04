# Kubernetes Nginx Deployment 

This repository contains a simple Kubernetes configuration to deploy an **Nginx web server** in a scalable and cloud-ready environment.

##  Features
-  **Kubernetes Deployment**: Runs multiple replicas of Nginx
-  **LoadBalancer Service**: Exposes the application to external traffic
-  **Scalability**: Easily scale Nginx instances
-  **Cloud-Compatible**: Deploy on Minikube, AWS EKS, Google GKE, or Azure AKS

## Deployment Steps

### Apply the Kubernetes Configuration
Run the following command to deploy Nginx:
```sh
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
