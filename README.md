<div align="center">

<h1 align="center">Hi 👋, I'm Rushikesh Satwadhar</h1>

<h3 align="center">DevOps • Cloud • Automation • Infrastructure as Code</h3>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=25&duration=2500&pause=1000&center=true&vCenter=true&width=850&lines=AWS+Cloud+Engineer;DevOps+Engineer;Kubernetes+Administrator;Docker+Containerization;Terraform+%7C+Ansible;Jenkins+CI%2FCD;Linux+Automation+with+Bash;Always+Learning+New+Technologies" />
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/rushikeshsatwadhar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rushisatwadhar23@gmail.com)
[![Location](https://img.shields.io/badge/📍_Pune,_India-Remote_Open-28a745?style=for-the-badge)](#)

</div>

---

## 🚀 About Me

Network Engineer with **2 years of hands-on experience** in configuring, monitoring, and troubleshooting enterprise network infrastructure. Currently developing expertise in DevOps and Cloud technologies, with practical experience in AWS, Terraform, Docker, Jenkins, Git, and Linux. Built hands-on projects to automate infrastructure provisioning and CI/CD pipelines, with a strong interest in cloud infrastructure, automation, and containerization. Continuously expanding my knowledge of Kubernetes and cloud-native technologies.

- 🔭 Currently: Learning and building hands-on DevOps projects using AWS, Terraform, Docker, Jenkins, and Kubernetes
- 🌱 Focus: DevOps, Cloud Computing, Infrastructure as Code (IaC), CI/CD, and Kubernetes
- 💬 Ask me about: Networking, AWS, Terraform, Docker, Jenkins, Linux, Git, Kubernetes, CI/CD
- 📫 Reach me: rushisatwadhar23@gmail.com
- ⚡ Open to: DevOps Engineer | Cloud Engineer | Platform Engineer | Remote & On-site opportunities across India
___

## 👀 Profile Views

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rushikeshsatwadhar&label=Profile%20Views&color=0e75b6&style=for-the-badge" />
</p>

___

## 🛠️ Tech Stack

<p align="center">

<img src="https://skillicons.dev/icons?i=linux" />&nbsp;
<img src="https://skillicons.dev/icons?i=bash" />&nbsp;
<img src="https://skillicons.dev/icons?i=git" />&nbsp;
<img src="https://skillicons.dev/icons?i=github" />&nbsp;
<img src="https://skillicons.dev/icons?i=githubactions" />&nbsp;
<img src="https://skillicons.dev/icons?i=docker" />&nbsp;
<img src="https://skillicons.dev/icons?i=kubernetes" />&nbsp;
<img src="https://cdn.simpleicons.org/helm/0F1689" width="48" height="48" />&nbsp;
<img src="https://cdn.simpleicons.org/argo/EF7B4D" width="48" height="48" />&nbsp;
<img src="https://skillicons.dev/icons?i=jenkins" />&nbsp;
<img src="https://skillicons.dev/icons?i=terraform" />&nbsp;
<img src="https://skillicons.dev/icons?i=ansible" />&nbsp;
<img src="https://skillicons.dev/icons?i=aws" />&nbsp;
<img src="https://skillicons.dev/icons?i=nginx" />&nbsp;
<img src="https://skillicons.dev/icons?i=prometheus" />&nbsp;
<img src="https://skillicons.dev/icons?i=grafana" />&nbsp;
<img src="https://skillicons.dev/icons?i=mysql" />&nbsp;
<img src="https://skillicons.dev/icons?i=java" />&nbsp;
<img src="https://skillicons.dev/icons?i=maven" />&nbsp;
<img src="https://skillicons.dev/icons?i=python" />&nbsp;
<img src="https://skillicons.dev/icons?i=vscode" />&nbsp;
<img src="https://skillicons.dev/icons?i=ubuntu" />

</p>

---

## 📂 DevOps Projects

### 🏗️ [AWS 3-Tier Architecture with Terraform]
Tech Stack: AWS • Terraform • EC2 • VPC • RDS • ALB • IAM • Auto Scaling 

Designed and provisioned a production-ready 3-tier AWS infrastructure using reusable Terraform modules, following Infrastructure as Code (IaC) best practices.

### 🚀 Key Features

* Provisioned a **production-ready AWS 3-tier architecture** using **Terraform**.
* Built a custom **VPC** with public, private, and database subnets across **2 Availability Zones**.
* Configured **Application Load Balancer (ALB)** and **EC2 Auto Scaling Groups** for high availability and scalability.
* Deployed **Amazon RDS MySQL** in private subnets with encrypted storage.
* Implemented **IAM least-privilege** access and **AWS Systems Manager (SSM)** for secure, SSH-free instance management.
* Developed **modular and reusable Terraform code** following Infrastructure as Code (IaC) best practices.

🛠️ Technologies Used
- Terraform
- AWS
- Amazon VPC
- Public & Private Subnets
- EC2
- Application Load Balancer (ALB)
- Security Groups
- Internet Gateway
- NAT Gateway
- Elastic IP
- Route Tables
- MySQL
- Apache Web Server

---

### 🚀 [cicd-jenkins-pipeline]
> **Jenkins · Docker · AWS ECR · EC2 · GitHub Actions · Trivy**

End-to-end CI/CD pipeline — zero manual steps from code push to production deploy.
- 10-stage pipeline: Checkout → Lint → Test → Docker Build → Trivy Scan → ECR Push → Deploy → Health Check → Notify
- Multi-stage Dockerfile (60% smaller final image, no devDependencies in prod)
- Branch strategy: `feature/*` → test only | `develop` → staging | `main` → production
- Slack notifications on every build (pass and fail)

---

### ☸️ [kubernetes-eks-deployment]
> **Kubernetes · AWS EKS · Terraform · Helm · Kustomize · HPA**

Production-grade Kubernetes deployment with zero-downtime rolling updates and auto-scaling.
- Liveness + Readiness + Startup probes on all pods
- HPA auto-scales 2→10 pods based on CPU (70%) and memory (80%)
- Kustomize overlays: dev (1 replica) and prod (3 replicas) from one base
- PodDisruptionBudget ensures minimum availability during cluster upgrades
- EKS cluster provisioned with Terraform, OIDC for IRSA

---

### 📊 [devops-monitoring-datadog]
> **Datadog · Terraform · DaemonSet · Synthetics · Log Pipelines**

Full observability stack — metrics, logs, traces, uptime checks, and alerts as code.
- 8 production monitors (CPU, memory, error rate, latency, pod crashes, RDS, disk)
- Synthetic uptime checks from Mumbai, Singapore, and US every 60 seconds
- Datadog DaemonSet on EKS — 1 agent per node, full cluster visibility
- Log pipelines with Grok parsers, GeoIP enrichment, HTTP status categorisation
- All dashboards and monitors managed via Terraform (Monitoring as Code)

---

---

## 🔥 GitHub Streak

<p align="center">

<img src="https://streak-stats.demolab.com?user=rushikeshsatwadhar&theme=tokyonight&hide_border=true"/>

</p>

---
## 📈 Contribution Graph

<p align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rushikeshsatwadhar&theme=tokyo-night&hide_border=true"/>

</p>
___

## 💼 Work Experience

| Role | Company | Period |
|---|---|---|
| Network Engineer | TCL | Aug 2023 – Aug 2025 |

---

## 🎓 Education

- **B.E in Computer Science & Engineering** —  Marathwada Institute of Technology (MIT), Aurangabad  | CGPA: 7.2

---

## 📬 Let's Connect

I'm actively looking for **remote DevOps / Cloud Engineer** roles in India (5 - 7 LPA+).
If you're hiring or know someone who is — let's talk!

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/rushikeshsatwadhar)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rushisatwadhar23@gmail.com)

---

<div align="center">
<i>⭐ If you find my projects useful, consider giving them a star — it helps others discover them!</i>
</div>
