<div align="center">

<!-- ANIMATED HEADER BANNER (AZURE TO CYBER CYAN WAVE) -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:020D1A,35:0078D4,100:00F2FE&height=220&section=header&text=MD%20IRSHAD%20ALAM&fontSize=48&fontColor=ffffff&fontAlignY=42&animation=fadeIn" alt="MD Irshad Alam Header Banner" width="100%" />

<!-- ANIMATED TYPING SVG HEADLINE -->
<a href="https://www.linkedin.com/in/md-irshad-alam-0a5278220">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&pause=1100&color=00F2FE&center=true&vCenter=true&width=900&height=50&lines=Senior+Azure+DevOps+Engineer+%26+Multi-Cloud+Architect;Microsoft+Azure+%7C+AWS+%7C+Google+Cloud+(GCP);Enterprise+IaC+with+Terraform+%26+Ansible;Kubernetes+(AKS)%2C+Docker+Containers+%26+Helm;DevSecOps+%7C+Checkov+%7C+Trivy+%7C+TFLint+%7C+SonarQube;11%2B+Years+IT+Experience+%7C+Ericsson+Global" alt="Animated Subtitle" />
</a>

<br/>

<!-- QUICK BADGES BAR -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/md-irshad-alam-0a5278220)
[![Cloud Experience](https://img.shields.io/badge/Cloud-Azure%20%7C%20AWS%20%7C%20GCP-232F3E?style=for-the-badge&logo=icloud&logoColor=white)](https://github.com/Irshad50)
[![Location](https://img.shields.io/badge/Location-Bangalore%2C%20India-blue?style=for-the-badge&logo=googlemaps&logoColor=white)](https://maps.google.com)

<br/>

<sub>📬 **Get in touch:** <a href="mailto:mdirshadalam91190@gmail.com">mdirshadalam91190@gmail.com</a></sub>

</div>

---

## 👨‍💻 Executive Summary

> **"Architecting scalable multi-cloud platforms, resilient automation pipelines, and zero-trust cloud infrastructure."**

I am a **Senior Azure DevOps Engineer & Multi-Cloud Infrastructure Architect** with **11+ years of total IT experience**, including **5+ years of specialized expertise** across Microsoft Azure, AWS, GCP, Terraform (IaC), Azure Kubernetes Service (AKS), CI/CD automation, and DevSecOps.

Currently driving cloud transformations at **Ericsson Global India**, architecting enterprise **Hub-and-Spoke Azure Landing Zones**, modular Terraform frameworks, automated deployment pipelines, and shift-left security controls.

* 🎯 **Core Domains:** Infrastructure as Code (Terraform), Cloud Architecture (Azure/AWS/GCP), Kubernetes (AKS), Enterprise CI/CD (Azure DevOps & GitHub Actions), DevSecOps.
* 💼 **Open To:** Senior & Lead Cloud/DevOps Architect Roles, Global Remote Consulting, and Enterprise Engineering Initiatives.

---

## 🏛️ Enterprise Multi-Cloud & DevOps Architecture Blueprint

```mermaid
flowchart LR
    subgraph Developer["👨‍💻 Developer & Version Control"]
        GIT["Git / GitHub / Azure Repos"] --> PR["Branching & Controlled Pull Requests"]
    end

    subgraph CI_CD["⚙️ Automated CI/CD & DevSecOps Gate"]
        PR --> PIPELINE["Azure DevOps / GitHub Actions"]
        subgraph Security["🛡️ Shift-Left Security Scans"]
            TFLINT["TFLint Syntax Check"]
            CHECKOV["Checkov IaC Compliance"]
            TRIVY["Trivy Container Scan"]
            SONAR["SonarQube Quality Gate"]
        end
        PIPELINE --> Security
    end

    subgraph IaC["🏗️ Infrastructure as Code"]
        Security --> TF["Terraform Core Engine"]
        TF --> BACKEND["Azure Blob Remote State + Concurrency Lease Locking"]
        TF --> MODULES["Reusable Enterprise Modules"]
    end

    subgraph MultiCloud["☁️ Enterprise Multi-Cloud Deployments"]
        MODULES --> AZURE["🔷 Microsoft Azure\n(Hub-Spoke VNet, AKS, Key Vault, App Gateway)"]
        MODULES --> AWS["🔶 Amazon Web Services\n(VPC, EKS, S3, IAM)"]
        MODULES --> GCP["🔴 Google Cloud Platform\n(VPC, GKE, Cloud Storage)"]
    end

    subgraph Monitoring["📊 Observability & Reliability"]
        AZURE & AWS & GCP --> OBS["Prometheus | Grafana | Azure Monitor | Log Analytics"]
    end

    classDef primary fill:#0078D4,stroke:#002050,stroke-width:2px,color:#fff;
    classDef security fill:#D83B01,stroke:#701200,stroke-width:2px,color:#fff;
    classDef cloud fill:#107C41,stroke:#043918,stroke-width:2px,color:#fff;
    class AZURE,AWS,GCP cloud;
    class Security,TFLINT,CHECKOV,TRIVY,SONAR security;
    class PIPELINE,TF,MODULES primary;
```

---

## 🧰 Technology Stack & Tooling

<div align="center">

### 🌐 Cloud, Containers & Automation Toolchain
[![Tech Stack](https://skillicons.dev/icons?i=azure,aws,gcp,terraform,kubernetes,docker,githubactions,ansible,linux,bash,powershell,python&perline=6)](https://skillicons.dev)

</div>

<br/>

| Domain | Enterprise Skills & Tools |
| :--- | :--- |
| ☁️ **Cloud Platforms** | **Microsoft Azure** (Primary), **AWS** (Amazon Web Services), **GCP** (Google Cloud Platform) |
| 🏗️ **Infrastructure as Code (IaC)** | **Terraform** (Reusable Modules, Dynamic Blocks, `for_each`, Workspaces, Remote State & Locking), **Ansible** |
| ☸️ **Containers & Orchestration** | **Kubernetes**, **Azure Kubernetes Service (AKS)**, **Docker**, Azure Container Registry (ACR), Helm |
| 🔄 **CI/CD & Source Control** | **Azure DevOps YAML Pipelines**, **GitHub Actions**, Git, GitHub, GitLab, Multi-stage Releases |
| 🌐 **Azure Networking** | Hub-and-Spoke Architecture, VNet Peering, Subnets, NSG, Azure Application Gateway, Azure Firewall, Bastion, Private Endpoints, Private DNS |
| 🛡️ **DevSecOps & Code Quality** | **Checkov**, **Trivy**, **tfsec**, **TFLint**, **Terrascan**, **Gitleaks**, **SonarQube**, Shift-Left IaC Scanning |
| 🔐 **Identity, Governance & Compliance** | Microsoft Entra ID (Azure AD), Azure RBAC, PIM (Privileged Identity Management), Azure Policy, Management Groups, Key Vault |
| 📈 **Observability & Reliability** | **Prometheus**, **Grafana**, **Azure Monitor**, Log Analytics Workspaces, Application Insights, Azure Site Recovery (ASR) |
| 💻 **Scripting & OS** | **Linux (RHEL/Ubuntu)**, **Bash**, **PowerShell**, **Azure CLI**, Python Automation |

---

## 🚀 Featured Enterprise Repositories

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🔷 <a href="https://github.com/Irshad50/terraform-azure-modules">terraform-azure-modules</a></h3>
      <p><b>Production-Ready Modular Azure Infrastructure</b></p>
      <p>Modular, highly scalable Terraform framework implementing Hub-Spoke VNets, Subnets, NSGs, Key Vault, and Compute with environment isolation (Dev, Stage, Prod).</p>
      <p>
        <img src="https://img.shields.io/badge/Terraform-HCL-844FBA?style=flat-square&logo=terraform" />
        <img src="https://img.shields.io/badge/Azure-Enterprise-0078D4?style=flat-square&logo=microsoftazure" />
        <img src="https://img.shields.io/badge/Architecture-Modular-success?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/Irshad50/terraform-azure-devops-pipeline">terraform-azure-devops-pipeline</a></h3>
      <p><b>Automated Azure DevOps CI/CD Multi-Stage Pipeline</b></p>
      <p>Enterprise YAML pipeline featuring automated linting, security scans (Checkov/TFLint), plan approvals, and zero-downtime execution with remote state synchronization.</p>
      <p>
        <img src="https://img.shields.io/badge/Azure_DevOps-YAML-0078D4?style=flat-square&logo=azuredevops" />
        <img src="https://img.shields.io/badge/DevSecOps-Checkov-orange?style=flat-square" />
        <img src="https://img.shields.io/badge/CI%2FCD-Automated-brightgreen?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 <a href="https://github.com/Irshad50/terraform-azure-landing-zone">terraform-azure-landing-zone</a></h3>
      <p><b>Enterprise Azure Landing Zone & Governance</b></p>
      <p>Scalable Cloud Adoption Framework (CAF) implementation using Management Groups, Azure Policy, RBAC, and centralized logging.</p>
      <p>
        <img src="https://img.shields.io/badge/Azure-Landing_Zone-0078D4?style=flat-square&logo=microsoftazure" />
        <img src="https://img.shields.io/badge/Governance-Azure_Policy-blue?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/Irshad50/terraform-remote-backend-state-locking">terraform-remote-backend-state-locking</a></h3>
      <p><b>Distributed State Management & Concurrency Locking</b></p>
      <p>Production setup for Terraform remote state stored in encrypted Azure Blob Storage with automated lease locking and access control.</p>
      <p>
        <img src="https://img.shields.io/badge/Terraform-Remote_State-844FBA?style=flat-square&logo=terraform" />
        <img src="https://img.shields.io/badge/Security-State_Locking-red?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛣️ <a href="https://github.com/Irshad50/terraform-azure-networking">terraform-azure-networking</a></h3>
      <p><b>Hub & Spoke Network Architecture via <code>for_each</code></b></p>
      <p>Enterprise networking blueprint provisioning VNets, subnets, peering, route tables, and NSG associations dynamically using nested maps.</p>
      <p>
        <img src="https://img.shields.io/badge/Networking-Hub--Spoke-blue?style=flat-square" />
        <img src="https://img.shields.io/badge/IaC-Advanced_Maps-blueviolet?style=flat-square" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏢 <a href="https://github.com/Irshad50/terraform-azure-prod">terraform-azure-prod</a></h3>
      <p><b>Production Infrastructure with Data Blocks & Reusable Modules</b></p>
      <p>Complete deployment of production VMs, NICs, Public IPs, and Storage Accounts utilizing Terraform Data Sources and secure credential injection.</p>
      <p>
        <img src="https://img.shields.io/badge/Production-Ready-success?style=flat-square" />
        <img src="https://img.shields.io/badge/Security-KeyVault-yellow?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

## 📊 Live GitHub Activity & Insights

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Irshad50&show_icons=true&theme=tokyonight&hide_border=false&count_private=true&title_color=00F2FE&icon_color=00FF87&text_color=FFFFFF&bg_color=0D1117" width="48%" alt="Irshad's GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Irshad50&layout=compact&theme=tokyonight&hide_border=false&title_color=00F2FE&text_color=FFFFFF&bg_color=0D1117" width="48%" alt="Irshad's Top Languages" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Irshad50&theme=tokyonight&hide_border=false&background=0D1117&ring=00F2FE&fire=00FF87&currStreakLabel=00F2FE" width="97%" alt="GitHub Streak" />

</div>

---

## 💼 Let's Connect & Collaborate

Whether you are looking to build or optimize enterprise Cloud & DevOps infrastructure:

* 💼 **LinkedIn:** [linkedin.com/in/md-irshad-alam-0a5278220](https://www.linkedin.com/in/md-irshad-alam-0a5278220)
* 📬 **Email:** `mdirshadalam91190@gmail.com`
* 📍 **Location:** Bangalore, India *(Open to Global Remote & Relocation)*

<div align="center">

<br/>

<!-- ANIMATED FOOTER WAVE -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F2FE,65:0078D4,100:020D1A&height=120&section=footer" width="100%" />

</div>
