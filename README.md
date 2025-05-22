# Three-Tier Web Application Deployment on AWS EKS using ArgoCD, Prometheus, Grafana, and Jenkins

![Three-Tier Banner](assets/Three-Tier.gif)

Welcome to the Three-Tier Web Application Deployment project! 🚀

This repository contains the implementation of a Three-Tier Web Application using ReactJS, NodeJS, and MongoDB, deployed on AWS EKS. The project demonstrates a comprehensive DevOps setup using a variety of modern tools and best practices for a robust and scalable environment.

## Table of Contents
- [Application Code](#application-code)
- [Jenkins Pipeline Code](#jenkins-pipeline-code)
- [Jenkins Server Terraform](#jenkins-server-terraform)
- [Kubernetes Manifests Files](#kubernetes-manifests-files)
- [Project Details](#project-details)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Application Code
The `Application-Code` directory contains the source code for the Three-Tier Web Application, including frontend and backend implementations.

## Jenkins Pipeline Code
The `Jenkins-Pipeline-Code` directory includes Jenkins pipeline scripts that automate the CI/CD process for seamless integration and deployment.

## Jenkins Server Terraform
Find Terraform scripts in the `Jenkins-Server-TF` directory to provision and configure the Jenkins server on AWS.

## Kubernetes Manifests Files
The `Kubernetes-Manifests-Files` directory contains Kubernetes manifests for deploying the application components on AWS EKS.

## Project Details
🛠️ **Tools Used:**
- Terraform & AWS CLI for infrastructure provisioning
- Jenkins, Sonarqube, Terraform, Kubectl, and more for CI/CD automation
- Helm, Prometheus, and Grafana for monitoring and visualization
- ArgoCD for GitOps-based continuous delivery

🚢 **High-Level Workflow:**
- AWS IAM user setup and infrastructure provisioning via Terraform
- Jenkins server deployment and integration with AWS
- EKS Cluster creation with Load Balancer setup
- Private ECR repositories for container image management
- Deployment of monitoring stack with Helm, Prometheus, and Grafana
- GitOps deployment strategy using ArgoCD for the Three-Tier application

📈 This project covers everything from infrastructure setup and CI/CD pipelines to monitoring and data persistence for a full production-ready deployment.

## Getting Started
Refer to the detailed guide to walk through IAM user creation, infrastructure provisioning, CI/CD setup, EKS cluster deployment, and application launch on AWS.

Happy Coding! 🚀
