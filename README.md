# 🎮 CloudPlay – CI/CD Tic Tac Toe on Kubernetes

🚀 A modern, cloud-native Tic Tac Toe game built with a complete **CI/CD pipeline using Jenkins, Docker, and Kubernetes** on AWS EC2.

---

## 🌟 Project Overview

**CloudPlay** is a lightweight web-based game designed to demonstrate real-world **DevOps practices**.
The application is fully containerized and automatically deployed using a CI/CD pipeline.

---

## 🧠 Key Highlights

* ⚡ Interactive Tic Tac Toe game (HTML, CSS, JavaScript)
* 🐳 Containerized using Docker
* 🔁 Automated CI/CD pipeline using Jenkins
* ☸️ Deployed on Kubernetes (Kind cluster on AWS EC2)
* 🌐 Exposed via NodePort service
* 🔄 Supports rolling updates for zero downtime deployment

---

## 🏗️ Architecture

```
GitHub → Jenkins → Docker → DockerHub → Kubernetes → Browser
```

---

## 🛠️ Tech Stack

| Category         | Tools/Technologies    |
| ---------------- | --------------------- |
| Frontend         | HTML, CSS, JavaScript |
| Containerization | Docker                |
| CI/CD            | Jenkins               |
| Orchestration    | Kubernetes (Kind)     |
| Cloud Platform   | AWS EC2               |
| Version Control  | Git & GitHub          |

---

## 📦 Project Structure

```
cloudplay-cicd-k8s/
│
├── index.html
├── style.css
├── script.js
├── Dockerfile
├── Jenkinsfile
└── k8s/
    ├── deployment.yaml
    └── service.yaml
```

---

## ⚙️ CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins pipeline is triggered automatically
3. Docker image is built and pushed to DockerHub
4. Kubernetes deployment is updated
5. Application is live with latest changes 🎉

---

## 🚀 Getting Started

### 🔹 Clone Repository

```
git clone https://github.com/your-username/cloudplay-cicd-k8s.git
cd cloudplay-cicd-k8s
```

### 🔹 Build Docker Image

```
docker build -t your-dockerhub-username/cloudplay .
docker push your-dockerhub-username/cloudplay
```

### 🔹 Deploy to Kubernetes

```
kubectl apply -f k8s/
```

---

## 📸 Screenshots (Add Here)

* Jenkins Pipeline Execution ✅
* Docker Image on DockerHub 🐳
* Kubernetes Pods Running ☸️
* Game UI 🎮

---

## 🎯 Resume Description

> Developed **CloudPlay**, a cloud-native Tic Tac Toe game with automated CI/CD pipeline using Jenkins, Docker, and Kubernetes on AWS EC2, enabling continuous deployment and scalable architecture.

---

## 📈 Future Enhancements

* 🎯 Add AI opponent (single-player mode)
* 🌐 Multiplayer support (WebSockets)
* 📊 Monitoring with Prometheus & Grafana
* 🔐 Secure deployment using Kubernetes Secrets
* 🚀 Helm chart packaging

---

## 🤝 Contributing

Feel free to fork this repository and enhance the project!

---

## 📬 Contact

**Avinash Wagh**
💼 Software Engineer | Cloud & DevOps Enthusiast
📧 [avinash.wagh@modiinnovations.com](mailto:avinash.wagh@modiinnovations.com)

---

⭐ If you like this project, give it a star!
