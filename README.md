# End-to-End CI Pipeline using GitHub Actions 🚀

## 📌 Overview
This repository demonstrates a **Continuous Integration (CI)** pipeline using **GitHub Actions**.
On every push to the `main` branch, the pipeline automatically builds a Docker image and pushes it to Docker Hub.

This project is part of a complete **CI + GitOps CD** DevOps workflow.

---

## 🧠 CI Responsibilities
- Source code management
- Docker image build
- Docker image push to Docker Hub
- Version-controlled CI workflow

---

## 🧱 Architecture (CI)

Developer Push

↓

GitHub Repository

↓

GitHub Actions (CI)

↓

Docker Build

↓

Docker Hub (Image Registry)

---

## 🛠 Tech Stack

- GitHub Actions

- Docker

- Docker Hub

- Python (sample backend)

---

## 📂 Repository Structure

---

├── app.py
|
├── requirements.txt
|
├── Dockerfile
|
├── .github/ 
| └── workflows/
| |
│ └── ci.yaml
|
└── README.md

---

## ⚙️ CI Workflow
1. Developer pushes code to `main`
2. GitHub Actions triggers CI
3. Docker image is built
4. Image is pushed to Docker Hub

---

## 🔗 Related GitOps Repository (CD)
Kubernetes deployment is handled via GitOps using ArgoCD:

👉 [https://github.com/Sachintee/Gitops-K8s-Deployment-P2.git]

---

## 🎯 Key Learnings
- CI automation using GitHub Actions
- Docker image lifecycle management
- Separation of CI and CD responsibilities
- Industry-standard DevOps practices

---

## 👤 Author
Sachin
