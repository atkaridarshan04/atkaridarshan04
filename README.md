# Darshan Atkari

DevOps / Platform Engineering. I build cloud infrastructure, CI/CD pipelines, and observability systems, and I write most of it in Terraform, Go, Python, and GitHub Actions.

Below is a curated map of my DevOps-focused work, grouped by domain. Full repo list is on my profile.

## DevOps & Platform Engineering

- **[cloudnative-devops-blueprint](https://github.com/atkaridarshan04/cloudnative-devops-blueprint)** — End-to-end DevOps implementation on a full-stack application, built around best practices.
- **[clusterpilot](https://github.com/atkaridarshan04/clusterpilot)** — Full IaC EKS platform with a Streamlit chat agent that answers against live k8s state and CloudWatch history via AWS's eks-mcp-server.
- **[cndb-gitops](https://github.com/atkaridarshan04/cndb-gitops)** — Production GitOps pipeline: Kargo promotion, ArgoCD sync, Kustomize overlays, Argo Rollouts canaries, Istio traffic management, zero-trust security (mTLS, Kyverno, NetworkPolicies) on EKS/kind. The production GitOps slice of `cloudnative-devops-blueprint`, pulled into its own repo.

## Cloud & Infrastructure as Code

- **[aws-cloud-portfolio](https://github.com/atkaridarshan04/aws-cloud-portfolio)** — Collection of 14 AWS projects spanning serverless, event-driven messaging, AI/Bedrock, real-time streaming, and security patterns, ranging from beginner to advanced. The three platform repos below are its production-grade reference tier.
- **[terraform-aws-ec2-platform](https://github.com/atkaridarshan04/terraform-aws-ec2-platform)** — Production-grade HA AWS EC2 platform: ALB, ASG, RDS, EFS, WAF, Route53, ACM, observability.
- **[terraform-aws-container-platform](https://github.com/atkaridarshan04/terraform-aws-container-platform)** — Production-inspired AWS container platform: ECS, Fargate, load balancing, networking, security.
- **[aws-github-runners](https://github.com/atkaridarshan04/aws-github-runners)** — Terraform + Packer blueprint for self-hosted, ephemeral GitHub Actions runners on EC2 Spot with a custom AMI.
- **[terraform-aws-kubernetes-platform](https://github.com/atkaridarshan04/terraform-aws-kubernetes-platform)** — Production-ready AWS EKS platform: managed node groups, VPC networking, Gateway API ingress via Envoy Gateway, automated TLS with cert-manager.

## CI/CD

- **[devsecops-github-actions](https://github.com/atkaridarshan04/devsecops-github-actions)** — Production-grade DevSecOps pipeline with GitHub Actions, SonarCloud, Trivy, Gitleaks, containers, and Kubernetes delivery.
- **[shared-ci-actions](https://github.com/atkaridarshan04/shared-ci-actions)** — Reusable GitHub Actions building blocks for a two-stage container pipeline: build once, scan before push, promote by digest.
- **[github-gitlab-cicd-pipeline](https://github.com/atkaridarshan04/github-gitlab-cicd-pipeline)** — CI/CD pipeline implemented across both GitHub Actions and GitLab CI, with DevSecOps principles.
- **[jenkins-shared-library](https://github.com/atkaridarshan04/jenkins-shared-library)** — Reusable Groovy scripts for Jenkins pipelines.

## Observability

- **[otel-observability-lab](https://github.com/atkaridarshan04/otel-observability-lab)** — Hands-on OpenTelemetry lab: traces, metrics, logs, the Collector, symptom-based alerting, deliberate failure scenarios, and a lift to Kubernetes.

## MLOps

- **[mlops-platform-blueprint](https://github.com/atkaridarshan04/mlops-platform-blueprint)** — Cloud-native MLOps platform featuring DVC, MLflow, Argo Workflows, KServe, and Kubernetes-native model serving.

## Foundations

- **[docker-stack](https://github.com/atkaridarshan04/docker-stack)** — Containerized application stack featuring Flask, MySQL, Nginx, Docker Compose, and monitoring components.
- **[dockerfile-optimization](https://github.com/atkaridarshan04/dockerfile-optimization)** — Writing efficient and secure Dockerfiles: multi-stage builds, image slimming, security, and build performance.
- **[overthewire-bandit-challenge](https://github.com/atkaridarshan04/overthewire-bandit-challenge)** — Structured OverTheWire Bandit Challenge writeups: Linux shell fundamentals and basic security.

## Find me

- Portfolio: https://atkaridarshan.online
