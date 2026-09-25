<h1 align="center">Hi, I'm Muhammad Ahmad</h1>
<h3 align="center">DevOps and Cloud Engineer in training. Building secure, automated, zero-downtime delivery pipelines</h3>

---

### About Me

I'm a final-year BSIT student (CGPA 3.6) at Minhaj University Lahore, focused on DevOps and Cloud Engineering. I build practical, end-to-end infrastructure projects rather than isolated tutorials: pipelines that provision infrastructure, enforce security gates, deploy to Kubernetes, and monitor themselves in production-like conditions.

My background in networking and Linux system administration shapes how I design and troubleshoot systems. I care about why a pipeline is reliable, not just that it runs. I'm CEH-certified and actively fold application and supply-chain security (SAST, dependency scanning, secret scanning, image signing) into the CI/CD work I build.

- Currently building out my DevOps portfolio project by project, each targeting a specific gap: GitOps delivery, security-gated pipelines, IaC provisioning, and observability
- Deepening my Kubernetes, AWS, and infrastructure-automation-at-scale skills
- Final Year Project: SecureGitOps, a continuously-verified CI/CD pipeline with integrated attack simulation and a real-time security dashboard
- Open to DevOps internship and entry-level opportunities
- Reach me at as8322279@gmail.com

---

### Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
</p>

| Category | Tools |
|---|---|
| Cloud and IaC | AWS, Microsoft Azure, Terraform |
| Containers and Orchestration | Docker, Kubernetes, Helm, ArgoCD |
| CI/CD and Automation | Jenkins, GitHub Actions, Ansible |
| Observability | Prometheus, Grafana |
| Security and Supply Chain | Trivy, Gitleaks, Bandit, Syft (SBOM), Cosign, OWASP ZAP |
| Languages and Scripting | Python, Bash |
| Networking and Systems | Linux Administration, DNS, DHCP, Active Directory, OSPF, BGP, EIGRP, RIP |
| Certifications | Certified Ethical Hacker (CEH) |

---

### Featured Projects

#### [Zero-Downtime GitOps Pipeline](https://github.com/muhammad-ahmadd-shafiq/zero-downtime-gitops)
My flagship project and primary credential for DevOps roles. A GitOps-driven delivery pipeline for a Flask application that ships changes with zero downtime.
- Pipeline: GitHub Actions builds and pushes container images; ArgoCD continuously syncs and deploys to Kubernetes (k3s)
- Reliability: Rolling updates with no service interruption on deploy
- Observability: Prometheus metrics collection with Grafana dashboards
- Stack: GitHub Actions, ArgoCD, Kubernetes, k3s, Flask, Prometheus, Grafana

#### [DevSecOps Jenkins Pipeline](https://github.com/muhammad-ahmadd-shafiq/devsecops-jenkins-pipeline)
A security-gated Jenkins CI/CD pipeline built around the principle that a build should fail on a security violation, not just report one.
- Pipeline stages: Gitleaks (secret scanning), Bandit (SAST), Trivy FS (dependency/SCA), Trivy Config (IaC misconfiguration), Pytest, Docker build, Trivy image scan, Syft (SBOM generation), Cosign (image signing), push to GHCR, deploy, OWASP ZAP (DAST), Slack notification
- Infrastructure: Jenkins running in Docker with Docker-socket integration; credentials managed through the Jenkins Credentials Store
- Stack: Jenkins, Docker, Gitleaks, Bandit, Trivy, Syft, Cosign, OWASP ZAP, GHCR, Slack

#### [AWS Infrastructure Automation Platform](https://github.com/muhammad-ahmadd-shafiq/aws-infrastructure-automation-platform)
An end-to-end Infrastructure-as-Code pipeline proving hands-on Terraform and Ansible skills, not just resume bullet points.
- Provisioning: Terraform provisions a VPC and EC2 instance on AWS with remote state management
- Configuration: Ansible configures the provisioned infrastructure
- Automation: GitHub Actions runs plan/apply as an automated CI/CD workflow
- Structure: terraform/, ansible/, app/, .github/workflows/
- Stack: Terraform, Ansible, AWS (VPC, EC2), GitHub Actions

#### [Kubernetes Monitoring Stack](https://github.com/muhammad-ahmadd-shafiq/k8s-monitoring-stack)
A full observability stack for Kubernetes clusters, deployed the way production teams actually deploy monitoring.
- Deployment: kube-prometheus-stack installed via Helm on k3s
- Coverage: Cluster-level and application-level metrics, ready for dashboarding and alerting
- Stack: Kubernetes, k3s, Helm, Prometheus, Grafana

---

### Other Projects

| Project | Description | Stack |
|---|---|---|
| [LearnLoop DevOps](https://github.com/muhammad-ahmadd-shafiq/learnloop-devops) | End-to-end DevOps project: CI/CD, IaC, containerization, and cloud deployment in one workflow | Docker, Azure, CI/CD |
| [Kubernetes Flask Application](https://github.com/muhammad-ahmadd-shafiq/k8s-flask-app) | Flask app deployed on Kubernetes: containerization, orchestration, deployment config | Flask, Docker, Kubernetes |
| [Jenkins CI/CD Pipeline](https://github.com/muhammad-ahmadd-shafiq/jenkins-cicd-flask) | Jenkins pipeline for automated testing and deployment of a Python application | Jenkins, Python |
| [Ansible Server Setup](https://github.com/muhammad-ahmadd-shafiq/ansible-server-setup) | Automated, repeatable server provisioning and configuration | Ansible |

---

### Final Year Project: SecureGitOps

"SecureGitOps: A Continuously-Verified CI/CD Pipeline with Integrated Attack Simulation and Real-Time Security Dashboard"
Built in collaboration with a penetration-testing-focused teammate, this project extends the Zero-Downtime GitOps Pipeline with supply-chain security controls and structured red-team attack simulation, surfaced through a live web dashboard showing pipeline runs, deployment status, security scan results, and per-build security scores.

---

### Connect With Me

Email: as8322279@gmail.com
Open to DevOps internship and entry-level opportunities.
Explore my repositories below, or reach out. Happy to walk through the design decisions behind any of these pipelines.
