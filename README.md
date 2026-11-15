<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:020617,40:075985,100:06B6D4&height=180&section=header&text=Surendra%20Kumar&fontSize=48&fontColor=F8FAFC&fontAlignY=36&desc=AWS%20Cloud%20%E2%80%A2%20DevOps%20%E2%80%A2%20Infrastructure%20Automation&descSize=16&descColor=22D3EE&descAlignY=58&animation=fadeIn" alt="Header"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=720&lines=Building+cloud+infrastructure+that+scales;Automating+delivery+with+CI%2FCD+pipelines;Containers+%7C+Kubernetes+%7C+Terraform+%7C+AWS" alt="Typing animation"/>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-surendra--kumar--07-020617?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/surendra-kumar-07)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0B1120?style=for-the-badge&logo=linkedin&logoColor=22D3EE)](https://www.linkedin.com/in/somisetty-venkata-surendra-kumar-48b086320/)
[![Repositories](https://img.shields.io/badge/Repositories-075985?style=for-the-badge&logo=github&logoColor=white)](https://github.com/surendra-kumar-07?tab=repositories)

![Profile views](https://komarev.com/ghpvc/?username=surendra-kumar-07&label=PROFILE%20VIEWS&color=0891B2&style=flat-square)
![Followers](https://img.shields.io/github/followers/surendra-kumar-07?style=flat-square&color=0891B2&label=FOLLOWERS)

</div>

---

## 👨‍💻 About Me

```yaml
name:        Somisetty Venkata Surendra Kumar
role:        Aspiring AWS Cloud & DevOps Engineer
education:   B.Tech, Computer Science & Engineering
specialization: Cybersecurity, IoT & Blockchain Technology
focus:       Cloud infrastructure, CI/CD, containers, Infrastructure as Code
mindset:     Build. Automate. Deploy.
```

I'm a Computer Science student focused on cloud and DevOps engineering. I learn by building: every project here is a hands-on attempt to solve a real infrastructure problem, from automating deployments to securing cluster access and provisioning cloud resources as code.

**What I'm aiming for:** AWS Cloud Engineer · DevOps Engineer

<table>
<tr>
<td width="50%" valign="top">

### 🔭 Currently Working On
- Designing multi-service deployments on AWS
- Extending CI/CD pipelines with containerized stages
- Writing reusable Terraform modules
- Building dashboards with Prometheus & Grafana

</td>
<td width="50%" valign="top">

### 🌱 Currently Learning
- Kubernetes workloads, networking & autoscaling
- AWS architecture best practices (Well-Architected)
- Observability: metrics, logs & alerting
- Ansible configuration management

</td>
</tr>
</table>

---

## 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,linux,bash,python,docker,kubernetes,terraform,ansible,jenkins,git,github,githubactions,maven,prometheus,grafana,mysql,flask&perline=9" alt="Tech stack icons"/>

</div>

| Domain | Tools & Services |
|:--|:--|
| ☁️ **Cloud (AWS)** | EC2 · S3 · IAM · VPC · EBS · RDS · Lambda · CloudWatch · Route 53 · CloudFront |
| ⚙️ **CI/CD** | Jenkins · GitHub Actions · Maven · SonarQube · Nexus · GitHub Webhooks |
| 🐳 **Containers & Orchestration** | Docker · Kubernetes (RBAC, CSR, Namespaces) |
| 🏗️ **Infrastructure as Code** | Terraform · Ansible |
| 🐧 **Linux & Scripting** | Linux Administration · Bash · Python (Boto3, Flask) |
| 📊 **Monitoring** | CloudWatch · Prometheus · Grafana |
| 🌐 **Networking** | DNS · HTTP/HTTPS · TCP/IP · Load Balancing |
| 🗄️ **Databases** | MySQL · SQL · Amazon RDS |

---

## 🚀 Featured Projects

### 01 · ☁️ CloudWatchX: AWS Multi-Region Monitoring Dashboard

> A dashboard that collects and visualizes Amazon CloudWatch metrics across multiple AWS regions in one place.

```mermaid
flowchart LR
    A[AWS Regions] -->|CloudWatch Metrics| B[Python + Boto3]
    B --> C[Flask Backend]
    C --> D[Web Dashboard]
    subgraph Deployment
    E[Docker Container] --> F[Amazon EC2]
    end
    C -.-> E
```

- Pulls CloudWatch metrics from multiple regions using Boto3
- Flask-based dashboard for unified visualization
- Containerized with Docker for portable, repeatable deployments
- Hosted on Amazon EC2

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

[**→ View Repository**](https://github.com/surendra-kumar-07/CloudWatchX-Multi-Region-AWS-Infrastructure-Monitoring-Dashboard)

---

### 02 · ⚙️ CI/CD Automation: Jenkins Pipeline

> An automated delivery pipeline covering source control, build, code quality analysis, and artifact management.

```mermaid
flowchart LR
    A[Developer Push] --> B[GitHub]
    B -->|Webhook| C[Jenkins]
    C --> D[Maven Build]
    D --> E[SonarQube Analysis]
    E --> F[Nexus Artifact Repo]
```

- Pipeline triggered automatically through GitHub Webhooks
- Maven-driven build and test stage
- SonarQube static analysis for code quality
- Versioned artifacts published to Nexus

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Nexus](https://img.shields.io/badge/Nexus-1B1C30?style=flat-square&logo=sonatype&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

[**→ View Repository**](https://github.com/surendra-kumar-07/web-app)

---

### 03 · ☸️ Kubernetes RBAC: Secure Cluster Access Management

> Role-based access control for a Kubernetes cluster, giving users least-privilege access to namespace resources.

```mermaid
flowchart LR
    A[User Private Key] --> B[CSR]
    B --> C[Cluster CA Approval]
    C --> D[Signed Certificate]
    D --> E[kubeconfig Context]
    E --> F[Role + RoleBinding]
    F --> G[Namespace Resources]
```

- Certificate-based user authentication using the Kubernetes CSR workflow
- Namespace-scoped Roles and RoleBindings
- Fine-grained resource permission management

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

[**→ View Repository**](https://github.com/surendra-kumar-07)

---

### 04 · 🏗️ AWS Infrastructure Automation with Terraform

> Provisioning and managing AWS infrastructure as code with reusable, parameterized configurations.

```mermaid
flowchart LR
    A[Terraform Config] --> B[terraform init]
    B --> C[terraform plan]
    C --> D[terraform apply]
    D --> E[AWS Resources]
    E -.->|terraform destroy| F[Clean Teardown]
```

- Provider configuration and AWS resource provisioning
- Input variables and outputs for reusable configurations
- Full infrastructure lifecycle management (create, update, destroy)

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

[**→ View Repository**](https://github.com/surendra-kumar-07)

---

## 🏆 Achievements & Experience

| | |
|:--|:--|
| 🥇 **Best Paper Award** | ICICC 2026 |
| 📜 **Certification** | NPTEL: Operating System Fundamentals |
| 📜 **Certification** | HackerRank: SQL (Basic) |
| 💼 **Internship** | Python Django Intern, Assistive Infotech |
| 🎓 **Education** | B.Tech CSE (Cybersecurity, IoT & Blockchain Technology) |

---

## 🗺️ Learning Roadmap

```mermaid
flowchart LR
    A[Linux & Bash] --> B[AWS Core Services]
    B --> C[Docker]
    C --> D[Jenkins CI/CD]
    D --> E[Kubernetes]
    E --> F[Terraform & Ansible]
    F --> G[Prometheus & Grafana]
    G --> H[AWS Certification]
    style A fill:#075985,color:#fff
    style B fill:#075985,color:#fff
    style C fill:#075985,color:#fff
    style D fill:#075985,color:#fff
    style E fill:#0891B2,color:#fff
    style F fill:#0891B2,color:#fff
    style G fill:#0891B2,color:#fff
    style H fill:#334155,color:#fff
```

<sub>Dark blue = completed or hands-on · Light blue = in progress · Grey = upcoming</sub>

---

## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=surendra-kumar-07&show_icons=true&hide_border=true&bg_color=020617&title_color=22D3EE&icon_color=0EA5E9&text_color=F8FAFC" alt="GitHub stats"/>
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surendra-kumar-07&layout=compact&hide_border=true&bg_color=020617&title_color=22D3EE&text_color=F8FAFC" alt="Top languages"/>

<img width="75%" src="https://streak-stats.demolab.com?user=surendra-kumar-07&hide_border=true&background=020617&ring=0EA5E9&fire=22D3EE&currStreakLabel=22D3EE&sideLabels=F8FAFC&dates=94A3B8&currStreakNum=F8FAFC&sideNums=F8FAFC" alt="Streak stats"/>

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Contribution snake"/>

</div>

---

## 🤝 Let's Connect

I'm open to **internships, junior cloud/DevOps roles, and collaboration** on cloud and automation projects.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Follow-020617?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/surendra-kumar-07)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0B1120?style=for-the-badge&logo=linkedin&logoColor=22D3EE)](https://www.linkedin.com/in/somisetty-venkata-surendra-kumar-48b086320/)

**☁️ Engineer the cloud. Automate the future.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:075985,100:020617&height=120&section=footer" alt="Footer"/>

</div>
