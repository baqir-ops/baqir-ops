### Hi, I'm Muhammad Baqir 👋

🚀 DevOps / Cloud Engineer

I'm a DevOps Engineer focused on building **production-style infrastructure and
GitOps delivery pipelines** using Kubernetes, Terraform, AWS, and Argo CD.

---

### 🛠️ DevOps Tools & Technologies

![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-Argo%20CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Helm](https://img.shields.io/badge/-Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### 🏆 Flagship Project — Secure GitOps Platform on AWS EKS

A production-style, 4-repository GitOps platform: Terraform-provisioned
infrastructure, GitHub Actions CI/CD with OIDC (zero long-lived AWS keys),
Argo CD managing dev → staging → production continuously from Git, and a
full Prometheus/Grafana/Alertmanager observability stack.

- 🔐 GitHub OIDC federated auth — no static AWS credentials in CI/CD
- 📦 Immutable image promotion (dev → staging → production) via reviewed PRs, rollback via `git revert`
- 🔄 Argo CD auto-sync, self-healing, and drift pruning across 3 environments
- 📊 Live Prometheus/Grafana/Alertmanager stack with active ServiceMonitors
- 🛡️ Non-root containers, read-only root filesystem, dropped capabilities, least-privilege IAM

**Repos:**
- Platform / GitOps config → [secure-gitops-platform](https://github.com/baqir-ops/secure-gitops-platform)
- Infrastructure (Terraform) → [secure-gitops-infrastructure](https://github.com/baqir-ops/secure-gitops-infrastructure)
- Application → [secure-gitops-app](https://github.com/baqir-ops/secure-gitops-app)
- Helm Chart → [secure-gitops-helm-chart](https://github.com/baqir-ops/secure-gitops-helm-chart)

---

### 📂 Previous Projects

- **AWS ECS Flask CI/CD** — Production-style Flask deployment using Docker, Gunicorn, Amazon ECR, ECS Fargate, ALB, CloudWatch Logs, and GitHub Actions CI/CD → [aws-ecs-flask-cicd](https://github.com/baqir-ops/aws-ecs-flask-cicd)
- **Flask EKS HPA** — Flask on Kubernetes with HPA scaling (2–6 pods at 60% CPU), NGINX Ingress, liveness/readiness probes, and GitHub Actions CI/CD → [flask-eks-hpa](https://github.com/baqir-ops/flask-eks-hpa)
- **K8s Flask Deployment** → [k8s-flask-deployment](https://github.com/baqir-ops/k8s-flask-deployment)
- **Multi-Environment CI/CD** — GitFlow multi-stage pipelines across dev, staging, and prod → [multi-env-cicd](https://github.com/baqir-ops/multi-env-cicd)
- **Docker Compose Health Check** → [docker-compose-healthcheck](https://github.com/baqir-ops/docker-compose-healthcheck)
- **AWS Production Outage Simulation** — Simulated production outage and root cause analysis to practice incident response → [aws-production-outage-simulation](https://github.com/baqir-ops/aws-production-outage-simulation)

---

### 📫 Connect With Me

LinkedIn: [linkedin.com/in/baqir-nawaz-devops](https://www.linkedin.com/in/baqir-nawaz-devops)
Email: baqirnawazm@gmail.com
