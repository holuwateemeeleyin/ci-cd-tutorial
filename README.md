# 🚀 Automated CI/CD Pipeline: GitHub Actions to AWS
This project demonstrates a modern DevOps pipeline that automates the deployment of a containerized application. Instead of manually uploading code, every time you git push to the main branch, GitHub Actions builds a Docker image and deploys it to AWS App Runner

## 🏗️ Architecture
1. GitHub Actions: The "engine" that runs the automation.
2. Docker: Packages the application into a portable image.
3. Amazon ECR: A private registry where AWS stores your Docker images.
4. AWS App Runner: A fully managed service that hosts the web application and handles scaling.

## 🛠️ Prerequisites
Before starting, ensure you have:
1. An AWS Account.
2. Docker installed on your local machine (for testing).
3. A Dockerfile in your project root.
