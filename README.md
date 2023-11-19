# Voting app using K8s ( deployment & service ) 🎯

This project showcases the deployment of a highly available MongoDB replicaset across three zones and a stateless Node.js web application interacting with the MongoDB replicas. The infrastructure is built using Terraform modules on Google Cloud Platform (GCP). Below are the details of the project components and how to deploy them.

![Alt text](architecture.png)

# You wanna your App like this   ⁉️ " just follow me 😉 "


1. cd  **voting-app-deployment Folder**

2. **Run**


``
   kubectl apply -f kubectl apply -f result-app-deploy.yaml
   kubectl apply -f kubectl apply -f voting-app-deploy.yaml
   kubectl apply -f kubectl apply -f worker-deploy.yaml
   kubectl apply -f kubectl apply -f postgres-deploy.yaml
   kubectl apply -f kubectl apply -f redis-deploy.yaml

   kubectl apply -f kubectl apply -f redis-service.yaml
   kubectl apply -f kubectl apply -f result-app-service.yaml
   kubectl apply -f kubectl apply -f voting-app-service.yaml
   kubectl apply -f kubectl apply -f postgres-service.yaml
``