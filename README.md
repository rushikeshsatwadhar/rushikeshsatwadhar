<div align="center">

# 👋 Hi, I'm Rushikesh Satwadhar

### DevOps Engineer | AWS · Kubernetes · Terraform · Jenkins · Docker

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/rushikeshsatwadhar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rushisatwadhar23@gmail.com)
[![Location](https://img.shields.io/badge/📍_Pune,_India-Remote_Open-28a745?style=for-the-badge)](#)

</div>

---

## 🚀 About Me

Network Engineer with **2 years of hands-on experience** in configuring, monitoring, and troubleshooting enterprise network infrastructure. Currently developing expertise in DevOps and Cloud technologies, with practical experience in AWS, Terraform, Docker, Jenkins, Git, and Linux. Built hands-on projects to automate infrastructure provisioning and CI/CD pipelines, with a strong interest in cloud infrastructure, automation, and containerization. Continuously expanding my knowledge of Kubernetes and cloud-native technologies.

- 🔭 Currently: Building DevOps infrastructure on AWS + Kubernetes
- 🌱 Focus: Cloud-native architecture, IaC, and platform engineering
- 💬 Ask me about: AWS, Terraform, Docker, Kubernetes, Jenkins, CI/CD
- 📫 Reach me: rushisatwadhar23@gmail.com
- ⚡ Open to: Remote DevOps / Cloud Engineer roles across India

---

## 🛠️ Tech Stack

### ☁️ Cloud & Infrastructure
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![VPC](https://img.shields.io/badge/VPC-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![EKS](https://img.shields.io/badge/EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Route53](https://img.shields.io/badge/Route53-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

### ⚙️ DevOps & Automation
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

### 📊 Monitoring & Observability
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=flat-square&logo=datadog&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### 🐧 OS & Scripting
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### 🔀 Source Control
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

### 💻 Networking
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-0078D4?style=flat-square&logo=icloud&logoColor=white)
![DNS](https://img.shields.io/badge/DNS-4285F4?style=flat-square&logo=cloudflare&logoColor=white)
![DHCP](https://img.shields.io/badge/DHCP-FF6F00?style=flat-square&logo=serverfault&logoColor=white)
![Routing](https://img.shields.io/badge/Routing-0A66C2?style=flat-square&logo=cisco&logoColor=white)
![Switching](https://img.shields.io/badge/Switching-005073?style=flat-square&logo=cisco&logoColor=white)

---

## 📂 DevOps Projects

### 🏗️ [aws-3tier-terraform](https://github.com/ashutosh1998github/aws-3tier-terraform)
> **AWS · Terraform · EC2 · VPC · RDS · ALB · IAM**

Production-ready 3-tier AWS architecture provisioned entirely with Terraform modules.
- VPC with public (Web), private (App), and isolated (DB) subnets across 2 AZs
- Auto Scaling Groups with CPU-based scaling policy (scales at 70% CPU)
- ALB with health checks, RDS MySQL with encrypted storage
- IAM roles with least-privilege, SSM Session Manager (no SSH needed)

---

### 🚀 [cicd-jenkins-pipeline](https://github.com/ashutosh1998github/cicd-jenkins-pipeline)
> **Jenkins · Docker · AWS ECR · EC2 · GitHub Actions · Trivy**

End-to-end CI/CD pipeline — zero manual steps from code push to production deploy.
- 10-stage pipeline: Checkout → Lint → Test → Docker Build → Trivy Scan → ECR Push → Deploy → Health Check → Notify
- Multi-stage Dockerfile (60% smaller final image, no devDependencies in prod)
- Branch strategy: `feature/*` → test only | `develop` → staging | `main` → production
- Slack notifications on every build (pass and fail)

---

### ☸️ [kubernetes-eks-deployment](https://github.com/ashutosh1998github/kubernetes-eks-deployment)
> **Kubernetes · AWS EKS · Terraform · Helm · Kustomize · HPA**

Production-grade Kubernetes deployment with zero-downtime rolling updates and auto-scaling.
- Liveness + Readiness + Startup probes on all pods
- HPA auto-scales 2→10 pods based on CPU (70%) and memory (80%)
- Kustomize overlays: dev (1 replica) and prod (3 replicas) from one base
- PodDisruptionBudget ensures minimum availability during cluster upgrades
- EKS cluster provisioned with Terraform, OIDC for IRSA

---

### 📊 [devops-monitoring-datadog](https://github.com/ashutosh1998github/devops-monitoring-datadog)
> **Datadog · Terraform · DaemonSet · Synthetics · Log Pipelines**

Full observability stack — metrics, logs, traces, uptime checks, and alerts as code.
- 8 production monitors (CPU, memory, error rate, latency, pod crashes, RDS, disk)
- Synthetic uptime checks from Mumbai, Singapore, and US every 60 seconds
- Datadog DaemonSet on EKS — 1 agent per node, full cluster visibility
- Log pipelines with Grok parsers, GeoIP enrichment, HTTP status categorisation
- All dashboards and monitors managed via Terraform (Monitoring as Code)

---

## 📈 GitHub Stats

<div align="center">

![Ashutosh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ashutosh1998github&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ashutosh1998github&layout=compact&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=ashutosh1998github&theme=tokyonight&hide_border=true)

</div>

---
