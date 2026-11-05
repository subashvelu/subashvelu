<div align="center">

<img src="assets/banner.svg" alt="Subash V - Cloud and DevOps Engineer in the making" width="100%">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=D4A62A&center=true&vCenter=true&width=650&lines=Aspiring+Cloud+%26+DevOps+Engineer;AWS+%E2%80%A2+CI%2FCD+%E2%80%A2+Infrastructure+as+Code;GitHub+Actions+%2B+OIDC+keyless+deploys;Linux+%E2%80%A2+Bash+%E2%80%A2+Git" alt="Typing animation" />
</a>

**I build and automate AWS infrastructure: CI/CD pipelines, Infrastructure as Code, and secure, keyless deployments.**

<a href="https://d166dz9n7bj9t4.cloudfront.net"><img src="https://img.shields.io/badge/LIVE%20PROJECT-Intech%20Motors-d4a62a?style=for-the-badge&labelColor=0a0d11" alt="Live project"></a>
<a href="https://www.linkedin.com/in/subash-v-3295812b6"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="mailto:v.subashvelu2410@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>

</div>

---

### 👋 About me

- ☁️ I learn **AWS and DevOps by building real projects**, not only tutorials.
- 🏗️ I built and deployed a **live website for a car workshop in Mylapore, Chennai** on AWS (S3 + CloudFront) with automated CI/CD and an offline billing app for the owner.
- 🔐 I care about security basics: no stored AWS keys (OIDC), private buckets, least-privilege IAM.
- 🎯 Looking for **fresher Cloud / DevOps Engineer** roles. 📍 Chennai, India.

---

### 🛠️ Tech stack

**Hands-on (used in my projects)**

<img src="https://skillicons.dev/icons?i=aws,githubactions,git,linux,bash,nodejs,nextjs&theme=dark" alt="hands-on skills" />

**Learning next**

<img src="https://skillicons.dev/icons?i=terraform,docker,kubernetes,python,postgres,mongodb&theme=dark" alt="skills I am learning" />

<sub>Also exploring: Helm, serverless on AWS (Lambda, API Gateway, DynamoDB).</sub>

---

### 🚀 Featured projects

| Project | What it shows | Links |
|:--|:--|:--|
| **🚗 Intech Motors Site** | AWS **S3 + CloudFront** hosting, **CloudFormation**, **GitHub Actions with OIDC (no stored keys)**, offline billing PWA | [Code ➜](https://github.com/subashvelu/intech-motors-site) · [Live ➜](https://d166dz9n7bj9t4.cloudfront.net) |
| **🖥️ Linux Health Monitor** | Bash automation that tracks CPU, memory and storage and raises threshold alerts | [Code ➜](https://github.com/subashvelu/linux-health-monitor) |
| **☁️ AWS Cloud Setup** | VPC segmentation, Security Groups, IAM roles and EC2 architecture | [Code ➜](https://github.com/subashvelu/cloud-project) |
| **⚡ Maxera Website** | Next.js app with an automated integration and delivery workflow | [Code ➜](https://github.com/subashvelu/maxera-website) |

<details>
<summary><b>🔍 How the Intech Motors pipeline works</b></summary>

```mermaid
flowchart LR
  Dev([Developer]) -->|git push| GH[GitHub repo]
  GH --> GA[GitHub Actions]
  GA -->|OIDC token| IAM[AWS IAM role]
  GA -->|s3 sync| S3[(S3 private bucket)]
  GA -->|invalidate cache| CF[CloudFront]
  S3 --> CF
  User([Visitor]) -->|HTTPS| CF
```

</details>

---

### 🗺️ What I am building next

| | Project | Skills |
|:--:|:--|:--|
| ✅ | Static site on S3 + CloudFront with CI/CD | S3, CloudFront, IAM, OIDC, CloudFormation, GitHub Actions |
| 📅 | The same infrastructure rewritten in **Terraform** | Terraform, remote state |
| 📅 | Serverless quote-request API | Lambda, API Gateway, DynamoDB, SNS |
| 📅 | Security scanning in the pipeline | Checkov, Trivy, Dependabot |
| 📅 | Dockerised app with automated deploy | Docker, ECR, EC2 |

<sub>✅ done · 📅 planned</sub>

---

### 🐍 My contribution graph

<div align="center">
  <img src="https://raw.githubusercontent.com/subashvelu/subashvelu/output/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%" />
</div>

---

<div align="center">
  <sub>📫 Reach me on <a href="https://www.linkedin.com/in/subash-v-3295812b6">LinkedIn</a> or by <a href="mailto:v.subashvelu2410@gmail.com">email</a> · ⭐ A star is always appreciated</sub>
</div>
