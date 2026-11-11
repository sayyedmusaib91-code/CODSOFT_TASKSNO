# CodSoft DevOps Internship - Tasks Repository (`CODSOFT_TASKSNO`)

This repository contains all the completed tasks and practical implementations for the **CodSoft DevOps Virtual Internship Program**. Developed and maintained by **Musaib Sayyed**.

---

## 📋 Table of Contents
- [Task 1: Dockerized Web Application](#task-1-dockerized-web-application)
- [Task 2: Git & GitHub Workflow](#task-2-git--github-workflow)
- [Task 3: Nginx Web Server Deployment](#task-3-nginx-web-server-deployment)
- [Task 4: CI/CD Pipeline using GitHub Actions](#task-4-cicd-pipeline-using-github-actions)

---

### 🐳 Task 1: Dockerized Web Application
* **Objective:** Containerized a web application using Docker[cite: 7].
* **Implementation:** 
  * Written a custom `Dockerfile` to package the static website assets and Nginx dependencies[cite: 7].
  * Built and verified the Docker container locally[cite: 7].
* **Bonus Completed:** Pushed the container image to Docker Hub:
  * **Docker Image:** `musaibsayyed/codsoft-task1:latest`[cite: 7]

---

### 🌿 Task 2: Git & GitHub Workflow
* **Objective:** Implemented version control best practices and collaborative workflows[cite: 8].
* **Implementation:**
  * Created and connected the remote repository (`CODSOFT_TASKSNO`) to GitHub[cite: 8].
  * Managed feature branches, commits, and clean commit history[cite: 8].
* **Bonus Completed:** Configured `main` branch protection rules requiring pull request reviews and approvals before merging[cite: 8].

---

### 🌐 Task 3: Nginx Web Server Deployment
* **Objective:** Deployed and configured an Nginx web server on Ubuntu Linux[cite: 9].
* **Implementation:**
  * Hosted the static web pages via Nginx virtual host (`/var/www/html`)[cite: 9].
  * Configured custom error handling and tested server accessibility[cite: 9].
* **Bonus Completed:** Enabled HTTPS/SSL security using local self-signed certificates and domain mapping (`codsoft.local`)[cite: 9].

---

### ⚡ Task 4: CI/CD Pipeline using GitHub Actions
* **Objective:** Automated build and verification workflows using CI/CD pipelines[cite: 10].
* **Implementation:**
  * Created workflow configuration at `.github/workflows/ci-cd.yml`[cite: 10].
  * Configured automated triggers on code pushes and pull requests to the `main` branch[cite: 10].
  * Added validation steps to check project structure, test Dockerfile builds, and monitor pipeline execution[cite: 10].

---

## 👤 Author
* **Musaib Sayyed**  
* **Internship Program:** CodSoft DevOps Virtual Internship
