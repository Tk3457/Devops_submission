# DevOps Lab Exercises

A hands-on collection of DevOps exercises covering containerization, Kubernetes deployments, application scaling, container networking, security, monitoring, and CI/CD automation.

The repository is organized into individual exercises, each with its own instructions, configuration files, and application code where applicable.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Repository Structure](#repository-structure)
- [Exercises](#exercises)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Learning Outcomes](#learning-outcomes)
- [Notes](#notes)

## Overview

The purpose of this repository is to explore core DevOps practices through practical exercises. The tasks progress from deploying containerized applications to managing Kubernetes workloads, applying security controls, monitoring application metrics, and automating builds with Jenkins.

Each exercise is maintained in a separate directory to make its instructions, source code, and configuration files easy to locate.

## Technologies Used

- **Containerization:** Docker
- **Container Orchestration:** Kubernetes, Minikube, kubectl
- **Programming:** Python, Bash
- **Monitoring and Metrics:** Prometheus, Grafana
- **CI/CD:** Jenkins, Jenkins Pipelines
- **Security:** AppArmor
- **Testing:** Python testing tools
- **Version Control:** Git and GitHub

The tools used may vary by exercise.

## Repository Structure

```text
Devops_submission/
├── README.md
├── Exercise-1-Kubernetes-Getting-Started/
├── Exercise-2-Minikube-Kubectl-Flask/
├── Exercise-3-Minikube-Scaling-Flask-ReplicaSets/
├── Exercise-4-Docker-Networking/
├── Exercise-5-Docker-Security-AppArmor/
├── Exercise-6-Grafana-Realtime-Monitoring/
├── Exercise-7-Jenkins-CI-Automation/
├── Exercise-8-Jenkins-Hello-World/
├── Exercise-9-Jenkins-Multi-Stage-Pipeline/
└── Exercise-10-Minikube-Multi-Node-Multi-App/
```

## Exercises

### Exercise 1 — Kubernetes Getting Started
Introduction to Kubernetes fundamentals and the initial steps for working with a Kubernetes cluster.

### Exercise 2 — Minikube, kubectl and Flask
Deploying a Flask application in a local Kubernetes environment using Minikube, Docker, and Kubernetes deployment configuration.

### Exercise 3 — Scaling Flask with ReplicaSets
Exploring replica management and application scaling using Kubernetes ReplicaSets and multiple application instances.

### Exercise 4 — Docker Networking
Understanding container networking and configuring communication between containerized applications.

### Exercise 5 — Docker Security with AppArmor
Exploring container security using AppArmor profiles and testing restricted application operations.

### Exercise 6 — Real-Time Monitoring with Grafana
Working with application metrics, monitoring configuration, and alert rules using Prometheus and Grafana-related tooling.

### Exercise 7 — Jenkins CI Automation
Exploring continuous integration concepts and automating development workflows with Jenkins.

### Exercise 8 — Jenkins Hello World
Creating and running a basic Jenkins job or pipeline to understand the fundamentals of CI/CD automation.

### Exercise 9 — Jenkins Multi-Stage Pipeline
Working with a multi-stage Jenkins pipeline and a Python application, including application tests.

### Exercise 10 — Minikube Multi-Node, Multi-App Deployment
Creating a two-node Minikube cluster, deploying Nginx, scaling the deployment to four replicas, and inspecting pod placement across cluster nodes.

For detailed instructions, commands, and configuration information, refer to the README inside each exercise directory.

## Prerequisites

Install the tools required for the exercise you intend to run:

- Git
- Docker
- Minikube
- kubectl
- Python and pip
- Jenkins
- Prometheus and Grafana, where required
- Linux or a compatible environment for AppArmor-related exercises

Some exercises require additional setup, cluster resources, or permissions. Check the individual exercise README before running its commands.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Tk3457/Devops_submission.git
cd Devops_submission
```

### 2. Choose an exercise

Navigate to the directory for the exercise you want to explore.

```bash
cd Exercise-2-Minikube-Kubectl-Flask
```

### 3. Read the instructions

Open the exercise's `README.md` and follow its prerequisites and setup instructions.

### 4. Run and verify

Execute the relevant commands for that exercise. Where applicable, verify the result using tools such as `kubectl`, Docker commands, Jenkins build logs, or monitoring dashboards.

> **Note:** Not every exercise uses the same tools or runtime environment. Follow the instructions in the relevant exercise directory.

## Learning Outcomes

This collection provides practical exposure to:

- Containerizing applications and understanding Docker fundamentals.
- Deploying and scaling workloads in Kubernetes.
- Working with local Kubernetes clusters using Minikube.
- Understanding container networking and security controls.
- Exploring monitoring, metrics, and alerting.
- Building CI/CD workflows using Jenkins.
- Testing applications and troubleshooting deployment issues.
- Managing code and configuration files with Git and GitHub.

## Notes

- Review each exercise's README before execution.
- Verify that required tools and dependencies are installed.
- Some exercises may require configuration changes for your local environment.
- Results depend on your machine, installed versions, and available resources.
- Document testing results accurately; instructions alone do not indicate that an exercise has been executed successfully.

## Author

**Tejas Kumar**

GitHub: [@Tk3457](https://github.com/Tk3457)

---

This repository is intended for learning and practicing DevOps concepts through individual hands-on exercises.
