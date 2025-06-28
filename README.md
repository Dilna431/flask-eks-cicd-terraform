# flask-eks-cicd-terraform


A complete example of deploying a **Python Flask web service** on **AWS EKS** using **Terraform** for infrastructure, **Docker** for containerization, and **Jenkins** for CI/CD automation.

---

## Tech Stack

- **Python Flask** — lightweight web framework
- **Docker** — containerizes the application
- **AWS ECR** — stores Docker images
- **Terraform** — provisions VPC, EKS, and ECR
- **AWS EKS (Kubernetes)** — runs the containerized app
- **Jenkins** — automates build, test, deploy pipeline

---

## 📂 Project Structure  
├── app/ # Flask app source code  
│ ├── app.py  
│ └── requirements.txt  
├── infra/ # Terraform scripts  
│ ├── main.tf  
│ ├── vpc.tf  
│ ├── eks.tf   
│ ├── ecr.tf  
│ ├── outputs.tf  
│ └── variables.tf  
├── k8s/ # Kubernetes manifests  
│ ├── deployment.yaml  
│ └── service.yaml  
├── Dockerfile  
├── Jenkinsfile  
└── README.md   



