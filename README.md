# DevOps CI/CD Pipeline Project (Jenkins & Maven)

## Overview
This is my personal implementation of a CI/CD pipeline for a Java application.  
I built this project to understand how Jenkins and Maven can automate building, testing, and deploying applications in a real-world workflow.

## Tech Stack
- Jenkins – Automates CI/CD pipeline
- Maven – Build and test management
- GitHub – Source control and versioning
- Java – Application development
- Docker – Containerization (optional)
- Kubernetes – Deployment (optional)

## What I Did
- Created an end-to-end CI/CD pipeline for a sample Java app
- Automated code fetch, build, test, and deploy using Jenkins and Maven
- Connected the project to GitHub for continuous integration
- Built a Docker image and deployed it using Kubernetes with rolling updates
- Gained practical exposure to real-world DevOps workflows

## How it Works
1. Push code to GitHub
2. Jenkins detects the change and runs the pipeline automatically
3. Maven builds the app and runs tests
4. Docker image is created and optionally pushed to Docker Hub
5. Kubernetes deploys the application with zero downtime

## Author
Pratik Patil
