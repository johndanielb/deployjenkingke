# Jenkins app deployment on GKE cluster using GitHub Actions.


## Workflow

In this we have set up the following workflow

1. Checking out the Repository
2. Setting up the Environment for Building Application
3. Building the Application
4. Adding Google Cloud CLI to Environment
5. Setting up Gcloud CLI
6. Configuring Docker
7. Building the Docker Image
8. Publishing the Docker Image to Google Container Registry
9. Setting up Kustomize
10. Deploying the Jenkins Image to Google Kubernetes Engine
