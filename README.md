# team-docs-butterfly

## Project Description
This is a DevOps practice project that demonstrates the full application delivery lifecycle.
It includes Docker containerization, Kubernetes deployment, and a CI/CD pipeline setup.

## Team
- Dilnaz Zhymabekova — DevOps Engineer
- Aisuluu Sharipova — Application Development

## Technology Stack
- Git
- Docker
- Kubernetes
- Java
- CI/CD (GitHub Actions)

## Run Instructions

### 1. Clone the repository
git clone https://github.com/AisuluuSharipova/team-docs-butterfly

### 2. Build Docker image
docker build -t devops-app .

### 3. Run container
docker run -p 8080:8080 devops-app

### 4. Deploy to Kubernetes
kubectl apply -f k8s/
