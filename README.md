# Awesome-Multi-Account-Resource-Sharing

## Top Multi-Account Resource Sharing Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cross-Account Access, Resource Sharing & Self-Hosted Multi-Cloud Governance*  

**Last updated: October 2026**



This repository tracks notable **commercial multi-account resource sharing platforms** and **open-source projects** that enable organizations to share resources, enforce policies, and manage access across multiple cloud accounts, projects, and subscriptions — from AWS Resource Access Manager to open-source Crossplane and Terraform-based governance.



**Examples** include AWS Resource Access Manager, Azure Policy Guest Configuration, Google Cloud IAM Conditions, HashiCorp Consul Multi-Datacenter, Turbot Guardrails, Meshcloud, Spacelift, Crossplane, env0, and Scalr (the category leaders).



**Open-source emphasis**: Multi-account resource sharing and governance is a strong open-source domain. **Crossplane** leads as the Kubernetes-native control plane for cloud resources, **Terragrunt** and **Terramate** orchestrate Terraform across accounts, **Atlantis** and **Digger** enable PR-based Terraform workflows, and **Open Policy Agent** enforces cross-account policies. **Cloud Custodian** handles governance rules, **CloudQuery** provides cross-account asset inventory, and **Steampipe** enables SQL-based multi-account querying. **Consul** provides multi-datacenter service discovery. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Resource Access Manager](https://aws.amazon.com/ram/)**

  **AWS's native resource sharing service** — share resources across AWS accounts and organizational units . **Supports VPC subnets, Transit Gateways, License Manager, Route 53 Resolver, and more** . **Best for AWS multi-account sharing** .



- **[Azure Policy Guest Configuration](https://azure.microsoft.com/en-us/products/azure-policy/)**

  **Azure's policy enforcement** — audit and configure settings across subscriptions . **Best for Azure multi-subscription governance** .



- **[Google Cloud IAM Conditions](https://cloud.google.com/iam/docs/conditions-overview)**

  **Google Cloud's conditional access** — attribute-based access control across projects . **Best for GCP multi-project sharing** .



- **[HashiCorp Consul Multi-Datacenter](https://www.consul.io/)**

  **Service discovery across datacenters** — see Open-Source section for the core project.



- **[Turbot Guardrails](https://turbot.com/)**

  **Cloud governance platform** — policy enforcement and resource sharing across accounts . **Best for enterprise multi-cloud governance** .



- **[Meshcloud](https://meshcloud.io/)**

  **Multi-cloud management platform** — self-service cloud accounts with governance . **Best for enterprise multi-cloud** .



- **[Spacelift](https://spacelift.io/)**

  **IaC orchestration platform** — Terraform, OpenTofu, Pulumi, CloudFormation, and Kubernetes . **Best for complex multi-IaC workflows** .



- **[Crossplane (Upbound)](https://www.upbound.io/)**

  **Managed Crossplane** — see Open-Source section for the core project.



- **[env0](https://www.env0.com/)**

  **IaC automation platform** — self-service environments with guardrails . **Best for developer self-service** .



- **[Scalr](https://scalr.com/)**

  **Terraform automation and collaboration** — policy enforcement and cost management . **Best for enterprise Terraform governance** .



## Open-Source GitHub Projects



### Multi-Cloud Control Planes



- **[Crossplane](https://github.com/crossplane/crossplane)**

  **The leading Kubernetes-native cloud resource management platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Extends Kubernetes API to manage cloud resources** — provision and share AWS, Azure, and GCP resources from Kubernetes . **Compositions for reusable infrastructure patterns** . **Provider families for AWS, Azure, GCP, and more** . **The de facto open-source multi-account resource sharing control plane** . **Best for platform teams building internal developer platforms** .



- **[AWS Controllers for Kubernetes (ACK)](https://github.com/aws-controllers-kustomize/ack)**

  **AWS-native Kubernetes controllers**, Apache-2.0 licensed . **Manage AWS resources from Kubernetes** — S3, RDS, EKS, and more . **Cross-account resource management via IRSA** . **Best for AWS-centric Kubernetes deployments** .



- **[Azure Service Operator](https://github.com/Azure/azure-service-operator)**

  **Azure-native Kubernetes controllers**, MIT licensed . **Manage Azure resources from Kubernetes** . **Best for Azure-centric Kubernetes deployments** .



- **[GCP Config Connector](https://github.com/GoogleCloudPlatform/k8s-config-connector)**

  **GCP-native Kubernetes controllers**, Apache-2.0 licensed . **Manage GCP resources from Kubernetes** . **Best for GCP-centric Kubernetes deployments** .



### Infrastructure as Code Orchestration



- **[Terragrunt](https://github.com/gruntwork-io/terragrunt)**

  **Terraform wrapper for DRY configurations**, MIT licensed with **8,000+ GitHub stars** . **Orchestrates Terraform across accounts and environments** . **Keeps configurations DRY** . **Best for complex multi-account deployments** .



- **[Terramate](https://github.com/terramate-io/terramate)**

  **Orchestration and code generation for Terraform**, MPL-2.0 licensed . **Adds stacks, orchestration, and GitOps to Terraform** . **Best for scaling Terraform deployments** .



- **[Atlantis](https://github.com/runatlantis/atlantis)**

  **Terraform pull request automation**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Collaborative IaC via pull requests** . **Plan and apply from PR comments** . **Best for Terraform collaboration** .



- **[Digger](https://github.com/diggerhq/digger)**

  **Open-source Terraform Cloud alternative**, MIT licensed . **CI/CD-native IaC orchestration** . **Best for Terraform in CI/CD** .



- **[OpenTofu](https://github.com/opentofu/opentofu)**

  **Open-source Terraform fork**, MPL-2.0 licensed with **25,000+ GitHub stars** . **Community-driven under Linux Foundation** . **Best for Terraform without BSL concerns** .



- **[Pulumi](https://github.com/pulumi/pulumi)**

  **IaC with real programming languages**, Apache-2.0 licensed with **22,000+ GitHub stars** . **TypeScript, Python, Go, .NET, Java** . **Best for developer-centric IaC** .



### Policy & Governance



- **[Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa)**

  **General-purpose policy engine**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Unified policy enforcement across cloud, Kubernetes, and CI/CD** . **Best for cross-account policy enforcement** .



- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)**

  **Rules engine for cloud security and cost management**, Apache-2.0 licensed . **Policy-as-code for AWS, Azure, GCP** . **Best for multi-account governance** .



- **[Kyverno](https://github.com/kyverno/kyverno)**

  **Kubernetes-native policy management**, Apache-2.0 licensed with **6,000+ GitHub stars** . **Policy as Kubernetes resources** . **Best for Kubernetes policy** .



- **[Gatekeeper](https://github.com/open-policy-agent/gatekeeper)**

  **OPA-based Kubernetes policy controller**, Apache-2.0 licensed . **Policy enforcement for Kubernetes** . **Best for Kubernetes admission control** .



### Multi-Account Visibility



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**

  **Open-source cloud asset inventory**, MPL-2.0 licensed with **6,000+ GitHub stars** . **Extracts, transforms, and loads cloud configuration** across accounts . **SQL-queryable inventory** . **Best for multi-account asset visibility** .



- **[Steampipe](https://github.com/turbot/steampipe)**

  **Zero-ETL cloud API querying with SQL**, AGPL-3.0 licensed with **7,000+ GitHub stars** . **Query cloud resources with SQL** across accounts . **Best for multi-account resource exploration** .



- **[Consul](https://github.com/hashicorp/consul)**

  **Service discovery and service mesh**, MPL-2.0 licensed with **28,000+ GitHub stars** . **Multi-datacenter service discovery** . **Connect for mTLS** . **Best for multi-datacenter service discovery** .



### Additional Strong Open-Source Options



- **Terraform** — The IaC standard for multi-account provisioning .

- **Ansible** — Configuration management across accounts .

- **Pulumi** — IaC with programming languages .

- **Crossplane** — Kubernetes-native cloud resources .

- **OpenTofu** — Community Terraform fork .

- **OPA** — Policy-as-code enforcement .

- **Cloud Custodian** — Cloud governance rules .

- **CloudQuery** — Cloud asset inventory .

- **Steampipe** — SQL-based cloud querying .

- **Consul** — Multi-datacenter service discovery .



**Frameworks for building custom multi-account resource sharing solutions**: Combine **Crossplane** for Kubernetes-native multi-cloud resource management . Use **Terragrunt** or **Terramate** for Terraform orchestration across accounts . Deploy **Atlantis** or **Digger** for PR-based IaC workflows . Integrate **Open Policy Agent** for cross-account policy enforcement . Use **Cloud Custodian** for governance rules . Choose **CloudQuery** or **Steampipe** for multi-account asset visibility . Integrate **Consul** for multi-datacenter service discovery . Note that true enterprise multi-account governance with managed infrastructure, compliance certifications, and vendor-supported SLAs (Turbot, Spacelift, Scalr) remains primarily commercial territory; open-source stacks provide strong control planes, IaC orchestration, and policy enforcement foundations that require integration for complete multi-account governance.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Multi-account resource sharing platforms manage access to critical cloud resources and infrastructure. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.

- **Cross-account access requires careful IAM configuration** — misconfigured trust relationships can expose resources. Use least-privilege principles and audit regularly .

- **State management is critical for IaC** — remote state backends (S3, GCS, Azure Blob) with locking are essential for team collaboration across accounts. Never commit state files to Git .

- **License considerations**: Crossplane uses Apache-2.0, Terragrunt uses MIT, OpenTofu uses MPL-2.0, OPA uses Apache-2.0, and Consul uses MPL-2.0. Verify licensing against your use case before committing.

- The open-source ecosystem provides strong control planes, IaC orchestration, and policy enforcement foundations, but **managed infrastructure, compliance certifications, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for platform engineers, cloud architects, and organizations seeking multi-account governance sovereignty.**

Let's make multi-account resource sharing more open, transparent, and secure.
