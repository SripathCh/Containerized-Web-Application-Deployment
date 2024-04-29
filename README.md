# Containerized-Web-Application-Deployment

### Overview
This project involves deploying a Docker containerized web application on Kubernetes, managed through Rancher, with a CI/CD pipeline using Jenkins for automated build and deployment tasks.

### Quick Setup
- Build Docker Image: docker build --platform linux/amd64 -t my-web-app:2.0 .
- Push to DockerHub: docker tag my-web-app:2.0 sripathcherukuri/my-web-app:2.0 && docker push sripathcherukuri/my-web-app:2.0
- Deploy on Kubernetes via Rancher: Setup clusters on EC2 instances and deploy using the Kubernetes configurations.


**Note**: This code and repository are for showcasing my projects and are not intended for external use. 
