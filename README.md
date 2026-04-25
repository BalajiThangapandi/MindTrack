# MindTrack
(Deploy the given React application to a production ready state)
# Dockerization
Created a Dockerfile for the React application
Built Docker image using:
docker build -t brain-app .
Tested container locally
# AWS ECR
Created AWS ECR repository
Tagged Docker image
Pushed image to ECR
docker tag brain-app:latest <ecr-repo-url>
docker push <ecr-repo-url>
# Kubernetes Deployment
Created Kubernetes Deployment YAML
Created Service YAML
Applied configuration:
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
