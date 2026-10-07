# Awesome Multi-Account Resource Sharing 🌐 🚀

![Awesome Multi-Account Resource Sharing Banner](assets/banner.svg)

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License" />
  <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen.svg" alt="PRs Welcome" />
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 💡 Overview & Market Landscape

A curated list of **SaaS platforms** and **open-source projects** for cross-account access, multi-cloud resource sharing, policy enforcement, and infrastructure governance.

> 📊 **Market Size & Structure**: The Cloud Infrastructure Management & Governance Market is estimated at **$22.5 Billion** and is projected to reach **$58.2 Billion by 2030** (CAGR ~17.4%). The sector is **moderately fragmented**, featuring dominant hyper-scaler native services (AWS RAM, Azure Policy, GCP IAM) alongside rapidly growing multi-cloud orchestration and IaC platforms (Spacelift, HashiCorp, env0).

---

## 📋 Table of Contents 📑

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
- [Open-Source GitHub Projects](#-open-source-github-projects)
- [How to Contribute](#-how-to-contribute)
- [Star History](#-star-history)
- [Support & Community](#-support--community)
- [Disclaimer](#-disclaimer)

---

## 🏢 SaaS / Hosted Platforms

Below is a tabular overview of top commercial SaaS platforms providing multi-account resource sharing, governance, and Infrastructure-as-Code (IaC) orchestration. Sorted by company size / market valuation (descending).

| Platform 🚀 | Description 📝 | Company Size / Valuation 💰 | Pricing (Starting Tier) 💵 | Free Tier / Free Trial Limits 🎁 |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Cloud IAM Conditions](https://cloud.google.com/iam/docs/conditions-overview)** | Attribute-based access control & project resource sharing across GCP | **~$4.25 Trillion** (Alphabet Market Cap) | Included with GCP resource usage | Free $300 credits for 90 days; IAM conditions available at no extra charge |
| **[Microsoft Azure Policy](https://azure.microsoft.com/en-us/products/azure-policy/)** | Audit & policy enforcement across Azure multi-subscription environments | **~$3.90 Trillion** (Microsoft Market Cap) | Free for Azure native resources | 100% Free core service; $200 free credit for 30 days on new accounts |
| **[AWS Resource Access Manager](https://aws.amazon.com/ram/)** | Native AWS service to securely share VPC subnets, Transit Gateways & licenses across accounts | **~$2.76 Trillion** (Amazon Market Cap) | Free service (pay only for underlying resources) | 100% Free service (no extra charge for sharing) |
| **[HashiCorp Consul Multi-Datacenter](https://www.consul.io/)** | Multi-datacenter service discovery, mesh connectivity, & access control | **~$6.4 Billion** (Acquisition Valuation / ~$583M Revenue) | Starts at $0.027/hour per client unit (~$20/mo) | 30-day free trial on HashiCorp Cloud Platform (HCP) |
| **[Spacelift](https://spacelift.io/)** | Collaborative IaC platform for Terraform, OpenTofu, Pulumi, & CloudFormation | **~$73.6M Raised** (~$4M ARR) | Starter plan from $20,000/year (or custom tier) | Free Tier (up to 2 users, 1 concurrency) & 14-day free trial |
| **[env0](https://www.env0.com/)** | IaC automation platform providing self-service environments with strict guardrails | **~$60M Raised** (~$5.9M ARR) | Standard plan starting at ~$349/month | Free Tier (250 runs/mo, 30 active envs) & custom enterprise demos |
| **[Meshcloud](https://meshcloud.io/)** | Enterprise multi-cloud management platform for automated accounts & governance | **~$19.4M ARR** (Private) | Custom enterprise pricing (upon request) | Free custom live demo & proof-of-concept trial upon request |
| **[Turbot Guardrails](https://turbot.com/)** | Enterprise automated cloud governance, policy enforcement, & resource sharing | Private (~$1.2M ARR sub) | Usage-based starting at $0.05–$0.10/control/month | 14-day free trial for organizations with full onboarding |
| **[Scalr](https://scalr.com/)** | Flexible Terraform automation platform with drift detection & policy enforcement | Private Startup | Usage-based starting at ~$99/month | Free Tier (up to 50 runs/month) & 7-day free trial |

---

## 🔓 Open-Source GitHub Projects

Curated open-source control planes, IaC orchestrators, and governance engines. Sorted by GitHub_Stars_Count (descending).

| Project 🌟 | Description 📝 | License 📜 | GitHub_Stars ⭐️ |
| :--- | :--- | :--- | :--- |
| **[OpenTofu](https://github.com/opentofu/opentofu)** | Community-driven, open-source Terraform fork under Linux Foundation | MPL-2.0 | [![OpenTofu Stars](https://img.shields.io/github/stars/opentofu/opentofu?style=social&color=white)](https://github.com/opentofu/opentofu/stargazers) |
| **[Consul](https://github.com/hashicorp/consul)** | Multi-datacenter service discovery, configuration, and service mesh engine | MPL-2.0 | [![Consul Stars](https://img.shields.io/github/stars/hashicorp/consul?style=social&color=white)](https://github.com/hashicorp/consul/stargazers) |
| **[Pulumi](https://github.com/pulumi/pulumi)** | Infrastructure as Code using real programming languages (TypeScript, Python, Go) | Apache-2.0 | [![Pulumi Stars](https://img.shields.io/github/stars/pulumi/pulumi?style=social&color=white)](https://github.com/pulumi/pulumi/stargazers) |
| **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)** | General-purpose policy engine for unified cross-account & k8s policy enforcement | Apache-2.0 | [![OPA Stars](https://img.shields.io/github/stars/open-policy-agent/opa?style=social&color=white)](https://github.com/open-policy-agent/opa/stargazers) |
| **[Crossplane](https://github.com/crossplane/crossplane)** | Kubernetes-native control plane to compose and manage multi-cloud resources | Apache-2.0 | [![Crossplane Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=social&color=white)](https://github.com/crossplane/crossplane/stargazers) |
| **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** | Rules engine for cloud security, compliance, and multi-account cost governance | Apache-2.0 | [![Cloud Custodian Stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=social&color=white)](https://github.com/cloud-custodian/cloud-custodian/stargazers) |
| **[Terragrunt](https://github.com/gruntwork-io/terragrunt)** | DRY Terraform wrapper to orchestrate configurations across accounts & environments | MIT | [![Terragrunt Stars](https://img.shields.io/github/stars/gruntwork-io/terragrunt?style=social&color=white)](https://github.com/gruntwork-io/terragrunt/stargazers) |
| **[Atlantis](https://github.com/runatlantis/atlantis)** | Terraform pull request automation tool for GitOps and team collaboration | Apache-2.0 | [![Atlantis Stars](https://img.shields.io/github/stars/runatlantis/atlantis?style=social&color=white)](https://github.com/runatlantis/atlantis/stargazers) |
| **[Kyverno](https://github.com/kyverno/kyverno)** | Kubernetes-native policy management engine for validation, mutation, & generation | Apache-2.0 | [![Kyverno Stars](https://img.shields.io/github/stars/kyverno/kyverno?style=social&color=white)](https://github.com/kyverno/kyverno/stargazers) |
| **[Steampipe](https://github.com/turbot/steampipe)** | Zero-ETL engine to query multi-account cloud APIs with SQL | AGPL-3.0 | [![Steampipe Stars](https://img.shields.io/github/stars/turbot/steampipe?style=social&color=white)](https://github.com/turbot/steampipe/stargazers) |
| **[CloudQuery](https://github.com/cloudquery/cloudquery)** | High-performance open-source cloud asset inventory and ELT platform | MPL-2.0 | [![CloudQuery Stars](https://img.shields.io/github/stars/cloudquery/cloudquery?style=social&color=white)](https://github.com/cloudquery/cloudquery/stargazers) |
| **[Digger](https://github.com/diggerhq/digger)** | Open-source GitOps tool for Terraform in existing CI/CD pipelines | MIT | [![Digger Stars](https://img.shields.io/github/stars/diggerhq/digger?style=social&color=white)](https://github.com/diggerhq/digger/stargazers) |
| **[Gatekeeper](https://github.com/open-policy-agent/gatekeeper)** | OPA-based admission controller for policy enforcement in Kubernetes clusters | Apache-2.0 | [![Gatekeeper Stars](https://img.shields.io/github/stars/open-policy-agent/gatekeeper?style=social&color=white)](https://github.com/open-policy-agent/gatekeeper/stargazers) |
| **[AWS Controllers for Kubernetes (ACK)](https://github.com/aws-controllers-kustomize/ack)** | AWS-native Kubernetes controllers to manage AWS resources across accounts | Apache-2.0 | [![ACK Stars](https://img.shields.io/github/stars/aws-controllers-kustomize/ack?style=social&color=white)](https://github.com/aws-controllers-kustomize/ack/stargazers) |
| **[Azure Service Operator](https://github.com/Azure/azure-service-operator)** | Azure-native Kubernetes operator to provision Azure resources from Kubernetes | MIT | [![Azure Service Operator Stars](https://img.shields.io/github/stars/Azure/azure-service-operator?style=social&color=white)](https://github.com/Azure/azure-service-operator/stargazers) |
| **[Terramate](https://github.com/terramate-io/terramate)** | Stacks, code generation, and change detection for Terraform & OpenTofu | MPL-2.0 | [![Terramate Stars](https://img.shields.io/github/stars/terramate-io/terramate?style=social&color=white)](https://github.com/terramate-io/terramate/stargazers) |
| **[GCP Config Connector](https://github.com/GoogleCloudPlatform/k8s-config-connector)** | Google Cloud Kubernetes add-on for declarative GCP resource management | Apache-2.0 | [![Config Connector Stars](https://img.shields.io/github/stars/GoogleCloudPlatform/k8s-config-connector?style=social&color=white)](https://github.com/GoogleCloudPlatform/k8s-config-connector/stargazers) |

---

## 🤝 How to Contribute

Contributions are highly welcome! 💖 Follow these quick steps:

1. Fork this repository 🍴
2. Create your feature branch (`git checkout -b feature/awesome-addition`)
3. Add your entry to `README.md` following the tabular format 📝
4. Commit your changes (`git commit -m 'Add new multi-account sharing tool'`) 
5. Push to the branch (`git push origin feature/awesome-addition`) 🚀
6. Open a Pull Request! 🎉

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Multi-Account-Resource-Sharing&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Multi-Account-Resource-Sharing&type=date&legend=top-left)

---

## 💖 Support & Community

If you find this repository useful, please consider giving it a star ⭐️, sharing it with colleagues, or sponsoring the project!

- ⭐️ **Star & Share**: Click the star button at the top right to show support!
- 💬 **Join Discord**: Connect with cloud engineers on [Discord](https://discord.gg/jc4xtF58Ve).
- ☕ **Buy Me a Coffee**: Sponsor the maintainer on [GitHub Sponsors](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a community-curated awesome list intended for informational purposes.
- Cross-account access requires careful IAM design and regular security auditing.
- Verify license compliance and security posture prior to deploying tools in production environments.
