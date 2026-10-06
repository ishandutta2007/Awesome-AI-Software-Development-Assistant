# Awesome-AI-Software-Development-Assistant
# Awesome-AI-Software-Development-Assistant

# Awesome-Terraform-Infrastructure-as-Code 🏗️ ⚙️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Terraform Infrastructure as Code Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Terraform-Infrastructure-as-Code?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Terraform Infrastructure as Code Ecosystem

**Curated List of Commercial IaC Platforms & Open-Source Terraform Orchestration Tools**  
*Focused on Terraform Automation, State Management, Policy as Code, GitOps Workflows & Multi-Cloud Provisioning*  

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **Terraform infrastructure as code platforms**, **open-source IaC orchestration tools**, and **cloud provisioning frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *HCP Terraform*, *Spacelift*, and *env0*), or self-hostable open-source alternatives (like *Terragrunt*, *Atlantis*, *Terramate*, and *Crossplane*), this list covers category leaders, declarative configuration tools, and privacy-respecting infrastructure automation.

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The Terraform and IaC management market has undergone significant consolidation, with HashiCorp's acquisition by IBM in 2025 reshaping the landscape and the emergence of OpenTofu as a Linux Foundation-backed open-source alternative . Pricing models vary: HCP Terraform charges per resource under management , Spacelift and env0 use consumption-based pricing per environment or successful apply , and Scalr positions itself as a cost-effective drop-in replacement with per-run pricing .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[HCP Terraform (Terraform Cloud)](https://www.hashicorp.com/products/terraform)** ☁️ | HashiCorp (IBM) | ~$5 Billion (Acquisition) | $0.00014/resource/hour (Plus); $0.00028 (Enterprise) | **Free tier: 500 resources**; 30-day trial for Plus | **HashiCorp's managed Terraform platform** — Remote state management, VCS integration, Sentinel policy as code, and private module registry. **Sentinel is proprietary** and only available on HCP Terraform/Terraform Enterprise . |
| **[Spacelift](https://spacelift.io/)** 🚀 | Spacelift | Private | Custom per-environment pricing | **Free trial available**; no permanent free tier | **Multi-IaC orchestration platform** — Runs Terraform, OpenTofu, Terragrunt, Pulumi, CloudFormation, Kubernetes, and Ansible. Policy hooks at every lifecycle stage, custom runner images, and stack dependency chains . |
| **[env0 (env zero)](https://www.env0.com/)** ⚡ | env0 | Private | Custom per-apply or per-environment pricing | **Free-forever tier: 250 runs/month, up to 30 active environments**  | **Multi-IaC with FinOps focus** — Strong cost tracking, budget controls, and per-environment cost attribution. Supports Terraform, OpenTofu, Terragrunt, Pulumi, and CloudFormation . |
| **[Scalr](https://scalr.com/)** 🎯 | Scalr | Private | Per-run pricing; custom quotes | **Free tier available** | **Terraform/OpenTofu-only governance platform** — OPA before and after plan, 147 RBAC permissions, SSO, and free drift watching on standard plan. Deep Terraform depth rather than multi-tool breadth . |
| **[Terrateam](https://terrateam.io/)** 🐙 | Terrateam | Private | Custom pricing; **free for open-source** | **Free for open-source projects** | **GitHub-native GitOps for Terraform** — Runs Terraform, OpenTofu, CDKTF, and Terragrunt operations via pull requests. Open-source (MPL-2.0) with commercial SaaS offering . |
| **[Atlantis (Commercial Support)](https://www.runatlantis.io/)** 🏛️ | Various | N/A (Open Source) | Atlantis OSS free; commercial support via vendors | **Open-source free forever** | **PR automation for Terraform** — Listens for PR comments (`atlantis plan`, `atlantis apply`) and runs Terraform in response. Requires hosting, scaling, patching, and upgrades — typically 0.5–1 FTE to operate . |
| **[Terrakube](https://terrakube.org/)** 🏢 | Terrakube | Private | Custom pricing; **free for small teams** | **Free tier available** | **Open-source Terraform Cloud alternative** — Full remote-backend platform with state management, VCS integration, and RBAC. Self-hosted or managed . |
| **[Digger (OpenTaco)](https://digger.dev/)** 🦴 | Digger | Private | Pro: from $10/user/month (5-user minimum) | **Free for open-source** | **CI/CD orchestrator for Terraform** — Runs Terraform in your existing CI system (GitHub Actions, etc.). Open-source core with Pro tier for teams . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Terraform](https://github.com/hashicorp/terraform)** [![Stars](https://img.shields.io/github/stars/hashicorp/terraform?style=social&color=white)](https://github.com/hashicorp/terraform/stargazers)  
  **The industry-standard IaC tool**, BUSL-1.1 licensed (v1.6+; earlier versions MPL-2.0). ~42k+ stars. Declarative HCL configuration for provisioning cloud resources across AWS, Azure, GCP, and 3,000+ providers. State management, dependency resolution, and plan/apply workflow. **License change in 2023** led to the OpenTofu fork . 🏗️

- **[OpenTofu](https://github.com/opentofu/opentofu)** [![Stars](https://img.shields.io/github/stars/opentofu/opentofu?style=social&color=white)](https://github.com/opentofu/opentofu/stargazers)  
  **Open-source Terraform fork**, MPL-2.0 licensed. ~22k+ stars. Linux Foundation and CNCF Sandbox project. Drop-in replacement for Terraform 1.5.6+ with state encryption, provider caching improvements, and active community governance. Supported by Spacelift, env0, Scalr, and Terragrunt . 🍞

- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)** [![Stars](https://img.shields.io/github/stars/gruntwork-io/terragrunt?style=social&color=white)](https://github.com/gruntwork-io/terragrunt/stargazers)  
  **Thin wrapper for Terraform/OpenTofu**, MIT licensed. ~8k+ stars. Keeps configurations DRY across environments with inheritance, automatic remote state management, dependency ordering, and stack-wide deployment commands. Version 1.0 (April 2026) introduced formal unit/stack terminology and unified `--filter` system . 📦

- **[Terramate](https://github.com/terramate-io/terramate)** [![Stars](https://img.shields.io/github/stars/terramate-io/terramate?style=social&color=white)](https://github.com/terramate-io/terramate/stargazers)  
  **Orchestrator and code generator for Terraform/OpenTofu**, MPL-2.0 licensed. ~3.5k+ stars. Introduces stack concepts, global variables, and code generation to simplify environment management. Built-in change detection for faster CI/CD. Bundles provide reusable contracts between platform teams and application teams . 🗂️

- **[Atlantis](https://github.com/runatlantis/atlantis)** [![Stars](https://img.shields.io/github/stars/runatlantis/atlantis?style=social&color=white)](https://github.com/runatlantis/atlantis/stargazers)  
  **Terraform PR automation**, Apache-2.0 licensed. ~8k+ stars. Listens for pull request comments (`atlantis plan`, `atlantis apply`) and runs Terraform in response. The simplest way to get plan/apply output in PRs. **No native policy enforcement, RBAC, audit trail, or drift detection** — requires external tooling . 🏛️

- **[Crossplane](https://github.com/crossplane/crossplane)** [![Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=social&color=white)](https://github.com/crossplane/crossplane/stargazers)  
  **Kubernetes-based control plane for cloud infrastructure**, Apache-2.0 licensed. ~10k+ stars. CNCF graduated project. Turns cloud resources into Kubernetes custom resources with **continuous reconciliation** — automatically corrects drift without manual `terraform apply`. Compositions enable self-service infrastructure APIs for developers. **Prerequisite**: a healthy Kubernetes cluster . ☸️

- **[Terratest](https://github.com/gruntwork-io/terratest)** [![Stars](https://img.shields.io/github/stars/gruntwork-io/terratest?style=social&color=white)](https://github.com/gruntwork-io/terratest/stargazers)  
  **Go library for infrastructure testing**, Apache-2.0 licensed. ~8k+ stars. Write automated tests for Terraform, Packer, Kubernetes, and more using Go's testing framework. Stands up real infrastructure, validates behavior, and tears down. Complements `terraform test` for integration coverage . 🧪

- **[Checkov](https://github.com/bridgecrewio/checkov)** [![Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social&color=white)](https://github.com/bridgecrewio/checkov/stargazers)  
  **Static analysis for IaC**, Apache-2.0 licensed. ~7k+ stars. Scans Terraform, CloudFormation, Kubernetes, and more for security and compliance misconfigurations. **Plan-aware scanning** evaluates resolved values from `terraform plan`. Rich policy library and SARIF output for GitHub code scanning . 🔍

- **[tfsec](https://github.com/aquasecurity/tfsec)** [![Stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=social&color=white)](https://github.com/aquasecurity/tfsec/stargazers)  
  **Fast static security scanner for Terraform**, MIT licensed. ~7k+ stars. Optimized for speed in CI — runs in seconds on code diffs. Developer-friendly feedback with SARIF output. Best paired with Checkov for plan-aware deeper analysis . ⚡

- **[Terratag](https://github.com/env0/terratag)** [![Stars](https://img.shields.io/github/stars/env0/terratag?style=social&color=white)](https://github.com/env0/terratag/stargazers)  
  **Automatic tagging for Terraform resources**, MPL-2.0 licensed. ~1.5k+ stars. CLI tool that applies tags or labels across entire Terraform/Terragrunt files for AWS, GCP, and Azure resources. Ensures consistent cost allocation and compliance tagging . 🏷️

- **[Terrateam (OSS Core)](https://github.com/terrateamio/terrateam)** [![Stars](https://img.shields.io/github/stars/terrateamio/terrateam?style=social&color=white)](https://github.com/terrateamio/terrateam/stargazers)  
  **GitOps CI/CD for Terraform**, MPL-2.0 licensed. ~500+ stars. GitHub-native automation for Terraform, OpenTofu, CDKTF, and Terragrunt. Plan/apply via pull requests with policy checks. Commercial SaaS extends with additional governance features . 🐙

- **[Digger](https://github.com/diggerhq/digger)** [![Stars](https://img.shields.io/github/stars/diggerhq/digger?style=social&color=white)](https://github.com/diggerhq/digger/stargazers)  
  **CI/CD orchestrator for Terraform**, MIT licensed. ~4k+ stars. Runs Terraform in your existing CI system (GitHub Actions, GitLab CI, etc.) — no separate runner infrastructure. Open-source core with Pro tier for teams needing advanced features . 🦴

- **[Cloudify](https://github.com/cloudify-cosmo/cloudify-manager)** [![Stars](https://img.shields.io/github/stars/cloudify-cosmo/cloudify-manager?style=social&color=white)](https://github.com/cloudify-cosmo/cloudify-manager/stargazers)  
  **Orchestration-first cloud management platform**, Apache-2.0 licensed. ~300+ stars. TOSCA-based, NFV-native. Model-driven approach to multi-cloud orchestration. Alternative for teams needing standards-based orchestration beyond Terraform's scope . ☁️

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new Terraform/IaC platforms or open-source infrastructure automation software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Terraform-Infrastructure-as-Code&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Terraform-Infrastructure-as-Code&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this Terraform infrastructure as code repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, platform engineers, and DevOps leads.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- Terraform's license changed to BUSL-1.1 in 2023, leading to the OpenTofu fork under MPL-2.0 . **Review licensing implications** for your organization before standardizing on either tool. HCP Terraform's Sentinel policy framework is proprietary and unavailable in open-source alternatives .
- Open-source IaC tools (Terragrunt, Terramate, Atlantis, Crossplane) provide self-hosted ownership and transparency, but enterprise-grade SLA guarantees, managed state backends, and 24/7 support remain primarily commercial offerings. Crossplane requires an operational Kubernetes control plane as critical infrastructure . 🏗️

---

<p align="center">
  <b>Made with ❤️ for platform engineers, DevOps leads, and open-source infrastructure advocates.</b>
</p>
```
