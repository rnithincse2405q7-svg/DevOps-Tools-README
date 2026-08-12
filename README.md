# 🛠️ DevOps Tools Guide

![DevOps](https://placehold.co/1200x350/1f2937/ffffff?text=DevOps+Tools+Guide)

> A beginner-friendly repository documenting five essential DevOps technologies: **Git, Docker, Jenkins, Kubernetes, and AWS**.

---

## 📖 Overview

This repository provides a quick reference for commonly used DevOps tools. Each section explains the tool's **purpose**, provides its **official website**, shows a **badge**, and demonstrates one commonly used command.

## 📋 Tools at a Glance

| Tool          | Primary Purpose         | Common Command      |
| ------------- | ----------------------- | ------------------- |
| 🔀 Git        | Version control         | `git status`        |
| 🐳 Docker     | Containerization        | `docker ps`         |
| 🔨 Jenkins    | CI/CD automation        | `jenkins --version` |
| ☸️ Kubernetes | Container orchestration | `kubectl get pods`  |
| ☁️ AWS        | Cloud computing         | `aws s3 ls`         |

---

# 🔀 Git

![Git Badge](https://img.shields.io/badge/Git-Version_Control-F05032?logo=git\&logoColor=white)

### 🎯 Purpose

**Git** is a distributed version control system used to track source-code changes, collaborate with other developers, and maintain different versions of a project.

### 🌐 Official Website

[Git Official Website](https://git-scm.com/?utm_source=chatgpt.com)

### 💻 Common Command

```bash
git status
```

The `git status` command displays the current state of the working directory and staging area.

### ⭐ Key Uses

* Track code changes
* Create and manage branches
* Collaborate with development teams
* Revert unwanted changes
* Maintain project history

---

# 🐳 Docker

![Docker Badge](https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker\&logoColor=white)

### 🎯 Purpose

**Docker** is a containerization platform that packages applications and their dependencies into portable containers, helping applications run consistently across environments.

### 🌐 Official Website

[Docker Official Website](https://www.docker.com/?utm_source=chatgpt.com)

### 💻 Common Command

```bash
docker ps
```

The `docker ps` command lists running containers.

### ⭐ Key Uses

* Package applications into containers
* Create reproducible environments
* Simplify application deployment
* Isolate application dependencies
* Support microservice architectures

---

# 🔨 Jenkins

![Jenkins Badge](https://img.shields.io/badge/Jenkins-CI%2FCD-D24939?logo=jenkins\&logoColor=white)

### 🎯 Purpose

**Jenkins** is an automation server commonly used to implement continuous integration and continuous delivery pipelines. The project provides both long-term-support and weekly release lines.

### 🌐 Official Website

[Jenkins Official Website](https://www.jenkins.io/?utm_source=chatgpt.com)

### 💻 Common Command

```bash
jenkins --version
```

This command displays the installed Jenkins version when the Jenkins command-line executable is available.

### ⭐ Key Uses

* Automate builds
* Run automated tests
* Create CI/CD pipelines
* Automate deployments
* Integrate development tools

---

# ☸️ Kubernetes

![Kubernetes Badge](https://img.shields.io/badge/Kubernetes-Container_Orchestration-326CE5?logo=kubernetes\&logoColor=white)

### 🎯 Purpose

**Kubernetes** is a container orchestration platform used to deploy, manage, scale, and maintain containerized applications.

### 🌐 Official Website

[Kubernetes Official Website](https://kubernetes.io/?utm_source=chatgpt.com)

### 💻 Common Command

```bash
kubectl get pods
```

This command displays the pods running in the currently selected Kubernetes context.

### ⭐ Key Uses

* Deploy containerized applications
* Scale workloads
* Perform service discovery
* Manage application rollouts
* Support highly available applications

---

# ☁️ AWS

![AWS Badge](https://img.shields.io/badge/AWS-Cloud_Computing-FF9900?logo=amazonaws\&logoColor=white)

### 🎯 Purpose

**Amazon Web Services (AWS)** is a cloud platform providing services across areas such as compute, storage, databases, networking, security, and developer tools.

### 🌐 Official Website

[AWS Official Website](https://aws.amazon.com/?utm_source=chatgpt.com)

### 💻 Common Command

```bash
aws s3 ls
```

This AWS CLI command lists Amazon S3 buckets accessible to the configured AWS credentials.

### ⭐ Key Uses

* Host applications in the cloud
* Store and retrieve data
* Provision compute resources
* Build scalable infrastructure
* Implement cloud-based DevOps pipelines

---

# 🔄 DevOps Workflow

The tools can work together in a typical software delivery workflow:

```text
Developer
    │
    ▼
  Git
    │
    ▼
 Jenkins ───────► Automated Tests
    │
    ▼
 Docker
    │
    ▼
 Kubernetes
    │
    ▼
   AWS
    │
    ▼
Production
```

---

# 📊 Comparison

| Tool           | Category         | Main Benefit                      | Example             |
| -------------- | ---------------- | --------------------------------- | ------------------- |
| **Git**        | Version Control  | Tracks source-code changes        | `git status`        |
| **Docker**     | Containerization | Portable application environments | `docker ps`         |
| **Jenkins**    | CI/CD            | Automates software delivery       | `jenkins --version` |
| **Kubernetes** | Orchestration    | Manages containers at scale       | `kubectl get pods`  |
| **AWS**        | Cloud            | Provides scalable infrastructure  | `aws s3 ls`         |

---

# 🖼️ DevOps Architecture

![DevOps Pipeline](https://placehold.co/1200x500/e5e7eb/111827?text=Git+%E2%86%92+Jenkins+%E2%86%92+Docker+%E2%86%92+Kubernetes+%E2%86%92+AWS)

---

# 📚 Learning Resources

* 🔀 Learn [Git](https://git-scm.com/)
* 🐳 Explore [Docker](https://www.docker.com/)
* 🔨 Learn [Jenkins](https://www.jenkins.io/)
* ☸️ Explore [Kubernetes](https://kubernetes.io/)
* ☁️ Learn [AWS](https://aws.amazon.com/)

---

## 💡 Important Note

> **DevOps is not just about using tools.** It is about improving collaboration, automation, reliability, and the speed at which software can be delivered.

---

## 🚀 Quick Start

1. Install **Git** for source-code management.
2. Install **Docker** for containerizing applications.
3. Set up **Jenkins** for automation and CI/CD.
4. Learn **Kubernetes** for container orchestration.
5. Use **AWS** to deploy and operate cloud infrastructure.
6. Combine the tools into an automated delivery pipeline.

---

## 📄 License

This documentation repository can be distributed under the **MIT License**.

---

⭐ **If this repository helps you learn DevOps, give it a star!**

<!-- End of README.md -->
