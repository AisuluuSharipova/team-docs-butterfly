# 🦋 Team Docs Butterfly – DevOps Project

## Project Description
This is a DevOps practice project that demonstrates the full application delivery lifecycle.
It includes Docker containerization, Kubernetes deployment, and a CI/CD pipeline setup.

# 👥 Team
- Dilnaz Zhumabaeva — DevOps Engineer
- Aisuluu Sharipova — Application Development
- Nuremir Sulaimanov — QA/Automation Engineer

## 🛠  Technology Stack
- Git
- Docker
- Kubernetes
- Java
- CI/CD (GitHub Actions)
- Linux

## 🚀 Getting Started

### 1. Clone the repository
git clone https://github.com/AisuluuSharipova/team-docs-butterfly

### 2. Build Docker image
docker build -t devops-app .

### 3. Run container
docker run -p 8080:8080 devops-app

### 4. Deploy to Kubernetes
kubectl apply -f k8s/

### 5. (Optional) Run tests
./run-tests.sh
