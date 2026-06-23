# Spring Boot Banking Application Deployment (Without CI/CD)

This repository demonstrates the complete manual deployment of a Spring Boot Banking Payment application to Kubernetes without using Jenkins, GitLab CI, GitHub Actions, or any CI/CD pipeline.

## What You'll Learn

* Create a Spring Boot application
* Build a JAR using Maven
* Create a Docker image
* Push the image to Nexus Repository
* Create Kubernetes Docker Registry Secrets
* Deploy the application to Kubernetes
* Expose the application using NodePort
* Validate and troubleshoot the deployment

## Technology Stack

* Java 17
* Spring Boot 3.2
* Maven
* Docker
* Nexus Repository
* Kubernetes

## Deployment Flow

```text
Developer
   ↓
Spring Boot Application
   ↓
Maven Build
   ↓
JAR File
   ↓
Docker Image
   ↓
Nexus Repository
   ↓
Kubernetes Deployment
   ↓
NodePort Service
   ↓
/payment Endpoint
```

## Complete Step-by-Step Documentation

👉 **Click below to view the full deployment guide:**

**https://github.com/openhelpdevops/devops_project1_withoutCICD/blob/main/manual-springboot-docker-kubernetes-deployment-v2.md**

The guide includes all commands, Dockerfile, Kubernetes YAML, command outputs, troubleshooting steps, architecture diagrams, and cleanup procedures.

---


