# DevOps Portfolio Project – Cloud‑Native CI/CD Application

## Project Overview

This project is designed to help students practice real-world DevOps skills by building and deploying a containerized application using modern DevOps tools and practices.

Students will clone this repository and implement a complete DevOps workflow that includes:

* Containerizing an application
* Building CI/CD pipelines
* Deploying to Kubernetes
* Implementing Infrastructure as Code
* Adding monitoring and observability

The goal is to simulate a real production DevOps environment.

---

# Learning Objectives

By completing this assignment, students will learn how to:

1. Work with Git and GitHub repositories
2. Containerize applications using Docker
3. Build CI/CD pipelines
4. Deploy applications to Kubernetes
5. Use Helm for Kubernetes deployments
6. Provision infrastructure using Terraform
7. Implement monitoring using Prometheus and Grafana

---

# Prerequisites

Students must have the following installed on their machines:

* Git
* Docker
* Kubernetes CLI (kubectl)
* Minikube OR any local Kubernetes cluster
* Helm
* Terraform
* AWS CLI (optional for cloud deployment)

Recommended OS:

* macOS
* Linux

---

# Step 1 – Clone the Repository

Clone the repository to your local machine.

```
 git clone <REPOSITORY_URL>
```

Navigate into the project directory.


---

# Step 2 – Understand the Application

The application is a simple Python web service.

Students should:

* Review the source code
* Understand how the application runs
* Identify required dependencies

Run the application locally:


---

# Step 3 – Containerize the Application

Create a Docker image for the application.

Tasks:

* Write or review the Dockerfile
* Build the Docker image
* Run the container locally


Verify the application works in a browser.

---

# Step 4 – Push the Image to a Container Registry

Students must push their Docker image to a container registry.

Tasks:

1. Create a DockerHub account
2. Tag the image
3. Push the image

---

# Step 5 – Create a Kubernetes Deployment

Students will deploy the application into a Kubernetes cluster.

Tasks:

* Create deployment.yaml
* Create service.yaml

Deploy the application:

Verify deployment:

---

# Step 6 – Deploy Using Helm

Helm will be used to package the Kubernetes deployment.

Tasks:

1. Create a Helm chart
2. Configure values.yaml
3. Deploy the chart

Commands:

---

# Step 7 – Implement CI/CD Pipeline

Students must create a CI/CD pipeline.

Pipeline requirements:

* Trigger on code push
* Build Docker image
* Scan the image
* Push the image to registry
* Deploy to Kubernetes

CI/CD can be implemented using GitHub Actions.

---

# Step 8 – Add Monitoring

Deploy monitoring tools in Kubernetes.

Students must:

* Install Prometheus
* Install Grafana
* Connect Prometheus to Grafana
* Import a Kubernetes dashboard

---

# Step 9 – Infrastructure as Code

Students will provision infrastructure using Terraform.

Tasks:

* Create a Terraform configuration
* Provision a Kubernetes cluster
* Deploy the application to the cluster

Optional:

Deploy the cluster on AWS.

---

# Assignment Deliverables

Students must submit:

1. GitHub repository link
2. Screenshot of running application
3. Screenshot of Kubernetes pods
4. Screenshot of CI/CD pipeline
5. Screenshot of Grafana dashboard

---


# Expected Outcomes

At the end of this project students should be able to:

* Design and deploy a DevOps pipeline
* Manage containerized workloads
* Deploy production‑style Kubernetes applications
* Implement monitoring and observability

---

