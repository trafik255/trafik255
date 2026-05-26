![AWS](https://img.shields.io/badge/AWS-Cloud-orange)
![EKS](https://img.shields.io/badge/Amazon_EKS-Kubernetes-326CE5)
![Helm](https://img.shields.io/badge/Helm-Packaging-0F1689)
![ArgoCD](https://img.shields.io/badge/ArgoCD-GitOps-EF7B4D)
![Karpenter](https://img.shields.io/badge/Karpenter-Node_Autoscaling-4B5563)
![Terraform](https://img.shields.io/badge/Terraform-IaC-623CE4)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF)
![SRE](https://img.shields.io/badge/Site_Reliability-Engineering-blue)
![Yardmaster](https://img.shields.io/badge/Yardmaster-K8s_Capacity_Intelligence-16A34A)

# About Me

Platform & Reliability Engineer focused on building cloud-native systems that survive contact with production.

I design AWS platforms with a practical bias: reliable enough to trust, simple enough to operate, cost-aware enough to scale, and automated enough that teams can ship without turning deployment into a ceremony. My recent work has moved deeply into production Kubernetes on EKS, including Helm-based workload packaging, ArgoCD-driven GitOps delivery, and Karpenter-backed compute strategy.

I like the hard middle of platform engineering: where infrastructure, CI/CD, observability, security controls, developer experience, and incident response all meet. The goal is not just to make something deploy. The goal is to make it understandable, recoverable, repeatable, and safe to change.

## Featured Project: Yardmaster

[Yardmaster](https://github.com/warehousegang/yardmaster) is a Kubernetes capacity intelligence tool I am building for platform teams. It watches workloads, nodes, scheduling events, and node pools, then turns raw cluster state into clear explanations and recommendations.

The goal is to help operators quickly understand why workloads are not scheduling, where capacity is being wasted, and which placement or resource constraints are making the cluster harder to operate. Yardmaster focuses on the problems Kubernetes teams actually chase during incidents and capacity reviews: pending pods, missing requests, overloaded node pools, inefficient bin packing, and workloads constrained by labels, taints, affinity, or topology rules.

In Yardmaster's model, workloads are Cargo, node pools are Tracks, and recommendations are Dispatches. The tool acts like an operations coordinator for Kubernetes capacity, helping teams move from scattered signals to actionable decisions.

## What I Build

* Production AWS platforms using EKS, VPC networking, IAM, ALB, CloudFront, WAF, and cost controls
* Kubernetes delivery systems using Helm, ArgoCD, GitOps workflows, environment promotion, and rollback patterns
* EKS compute models using Karpenter, workload-aware node provisioning, scheduling constraints, and cost-aware scaling
* Kubernetes capacity intelligence tools that explain scheduling failures, capacity waste, and workload placement constraints
* Terraform infrastructure for reproducible multi-environment systems and platform foundations
* CI/CD systems with GitHub Actions, containerized pipelines, deployment gates, validation, and failure recovery
* Observability foundations with metrics, logs, traces, dashboards, alerting, and incident-oriented runbooks
* Security and resilience controls for bot traffic, API abuse, production spikes, and external service cost risk

## Recent Work

* [VBC360 Dashboard](https://github.com/warehousegang/vbc360-dashboard) - Designed, built, and operated the full-stack application and platform, including infrastructure, CI/CD, and deployment architecture.
* Built and evolved EKS platform patterns with Helm charts, ArgoCD GitOps delivery, and Karpenter-driven node provisioning.
* Rebuilt and stabilized CI/CD systems under failure, with emphasis on repeatability, rollback, and clearer operational ownership.
* Designed distributed test execution patterns for Kubernetes-native CI validation and scalable workload execution.
* Implemented infrastructure and security controls to mitigate production traffic spikes, bot behavior, and API-driven cost risks.
* Designed and built [BusyNow](https://busynow.app) as an end-to-end cloud-native platform, owning application architecture, AWS infrastructure, and CI/CD.
* For hiring managers and recruiters who want more context, see [BusyNow public](https://github.com/warehousegang/busynow-public).

## Technical Depth

**Kubernetes & EKS**

* EKS cluster architecture, workload isolation, namespace strategy, ingress patterns, service exposure, and AWS integration
* Helm chart design for repeatable application packaging, configuration layering, and environment-specific values
* ArgoCD application models, GitOps sync workflows, declarative delivery, drift detection, and promotion patterns
* Karpenter provisioning strategy, node pool design, right-sized compute, disruption handling, and cost-aware autoscaling
* Kubernetes scheduling primitives including requests, limits, taints, tolerations, affinity, disruption budgets, and health probes

**AWS Platform Engineering**

* VPC design, private/public subnet strategy, routing, security groups, IAM boundaries, and service-to-service access
* Kubernetes platform design for production workloads, including cluster boundaries, delivery workflows, and operational ownership
* ALB, CloudFront, WAF, DNS, TLS, and edge controls for secure public application delivery
* Cost-aware infrastructure decisions, especially around autoscaling, traffic spikes, third-party APIs, and over-provisioning risk

**Infrastructure as Code & Delivery**

* Terraform modules, multi-environment state strategy, reproducible infrastructure, and reviewable change workflows
* GitHub Actions pipelines for build, test, container publishing, infrastructure validation, and deployment orchestration
* Deployment safety patterns including blue/green, canary, staged rollout, rollback, smoke tests, and health-based promotion
* GitOps operating models that keep production state reviewable, auditable, and recoverable from source control

**Reliability & Operations**

* SLO-minded service design, failure-mode analysis, alert quality, incident response, and practical runbooks
* Observability systems using Prometheus, Grafana, OpenTelemetry, structured logs, and application-level health signals
* Production guardrails for rate limiting, bot protection, API failure handling, degraded modes, and cost containment
* Test platform engineering for distributed execution, pipeline feedback, and system behavior validation

## Current Focus

I am currently building production-grade platform reference architectures and operational patterns around:

* EKS platform foundations with Helm, ArgoCD, GitOps, and Karpenter
* [Yardmaster](https://github.com/warehousegang/yardmaster), a Kubernetes capacity intelligence tool for scheduling, utilization, and node pool recommendations
* Kubernetes observability and incident response workflows
* Deployment safety patterns for application and infrastructure changes
* AWS cost controls, security boundaries, and reliability guardrails
* AI reliability work involving evaluation frameworks, guardrails, and behavior validation

## Contact

LinkedIn: https://www.linkedin.com/in/thomashow/  
GitHub: https://github.com/warehousegang
