# Hi, I'm Miren 👋

Cloud/Platform Engineer with 10+ years across Windows Server, cloud infrastructure, and automation. Currently at **Cisco** on the Windows & Device Automation teams, building platform tooling.

Everything below runs for real on a self-hosted home lab — Windows Server 2022 Hyper-V host, Ubuntu VMs, a k3s cluster with a GPU node, and Tailscale for remote access.

## What I do

- 🏗️ **CI/CD & Platform Engineering** — Reusable GitHub Actions workflows across 11 repos, with secret scanning, SHA-pinned actions and Sonar quality gates. Releases flow through Jenkins into ArgoCD.

- ☁️ **Infrastructure as Code** — Terraform modules for AWS (EKS on Fargate, IAM, VPC, Lambda) and for the CI platform itself. Currently layering in Terragrunt.

- 📊 **Observability & SRE** — Prometheus, Grafana, Loki and Alertmanager self-hosted on k3s, with custom instrumentation and dashboards shipped as code from my own Helm charts. The alerting has caught outages I'd otherwise have missed.

- 🤖 **AI/ML Infrastructure** — Qwen served on a GPU k3s node (RTX 4090) via KServe — load-tested, with TTFT and token latency tracked in Grafana. Plus an MCP server exposing 11 tools to LLMs.

- 💥 **Chaos Engineering** — Chaos Mesh under ArgoCD, running fault experiments against a steady-state hypothesis written before a fault.

- ⏱️ **Workflow Orchestration** — Temporal and Postgres on k3s for durable, code-defined workflows.

- ⚡ **Automation** — A device validation pipeline (PowerShell, Python, Intune, AWS, LLM triage, Webex) saving **45+ hours per quarter**.

## Featured Projects

| Project | What it is |
| --- | --- |
| [ci-platform](https://github.com/mirenchaps/ci-platform) | Reusable CI/CD platform — GitHub Actions workflows, Jenkins shared library steps, and Terraform modules. Evolved from Docker-based deployments to Kubernetes as the platform grew. |
| [home-lab-gitops](https://github.com/mirenchaps/home-lab-gitops) | GitOps source of truth for my k3s cluster — ArgoCD app-of-apps, Helm values, and GPU model serving with KServe. |
| [eks-fargate-terraform](https://github.com/mirenchaps/eks-fargate-terraform) | Production-shaped EKS on Fargate in Terraform — modular network, IAM, cluster and addons, bootstrapped with ArgoCD. |
| [home-network-mcp](https://github.com/mirenchaps/home-network-mcp) | MCP server on k3s — 11 tools for Windows Server metrics, Raspberry Pi health, network scanning and Homebridge control. Instrumented with per-tool Prometheus metrics and a dashboard shipped from its own Helm chart. |
| [observability-stack](https://github.com/mirenchaps/observability-stack) | Self-hosted Prometheus, Grafana, Loki and Alertmanager on k3s, deployed and managed via ArgoCD + Helm (GitOps). |
| [device-validation](https://github.com/mirenchaps/device-validation) | Automated device validation saving 45+ hrs/quarter — PowerShell, Intune, AWS, LLM triage, Webex. |

🌱 **Currently working on:** Getting my self-hosted LLM to write up the results of my own chaos experiments.

## Tech Stack

![python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![powershell](https://img.shields.io/badge/powershell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white)
![terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![aws](https://img.shields.io/badge/AWS-%23232F3E.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![loki](https://img.shields.io/badge/Loki-F2C94C?style=for-the-badge&logo=grafana&logoColor=black)
![sonarqube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white)
![linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![githubactions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![argocd](https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)
![helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![AI](https://img.shields.io/badge/AI_%2F_LLMs-D97757?style=for-the-badge&logo=claude&logoColor=white)

## Connect

[![linkedin](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miren-chaps)
[![opportunities](https://img.shields.io/badge/Open_to_Opportunities-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miren-chaps)
[![github](https://img.shields.io/badge/GitHub-%23100000.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mirenchaps)
