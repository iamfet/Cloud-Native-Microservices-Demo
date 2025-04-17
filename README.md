# 🚀 DevOps Project: Cloud-Native Microservices Demo

This project is a full DevOps pipeline built around a cloud-native microservices-based application inspired by Google’s [Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo). It demonstrates modern best practices in CI/CD, Kubernetes, observability, GitOps, and infrastructure as code (IaC).

---

## 📁 Project Structure

```
devops-microservices-demo/
│
├── src/                        # Source code of microservices (from Google repo)
│
├── helm-charts/               # Helm charts for Kubernetes deployments
│   └── <service-name>/        # Each microservice has its own chart
│
├── kubernetes-manifests/      # Raw Kubernetes YAMLs (optional)
│
├── argocd/                    # ArgoCD application and project configs
│   ├── apps/                  # App definitions for each microservice
│   └── projects/              # Project-level configs
│
├── infra/                     # Infrastructure as Code (Terraform)
│   ├── eks/                   # EKS cluster setup
│   ├── vpc/                   # Networking
│   └── s3/                    # S3 backend setup
│
├── .github/workflows/         # GitHub Actions for CI/CD
│
├── README.md                  # Project overview and documentation
│
└── docs/                      # Additional documentation and diagrams
```

---


## 🛠️ Tools & Technologies
- Kubernetes (EKS or kind/minikube)
- Docker
- Helm
- ArgoCD
- Terraform
- GitHub Actions
- Prometheus & Grafana
- OpenTelemetry


---


## 🚀 Features
- Kubernetes-native microservices architecture
- Helm for packaging and deploying services
- ArgoCD for GitOps-style continuous delivery
- GitHub Actions for Automated CI/CD pipelines
- Terraform for provisioning infrastructure
- Observability using Prometheus, Grafana, and OpenTelemetry
- Secure deployment pipeline and RBAC policies


---

## 🙋 Why This Project?

This project was built to:

- Showcase end-to-end DevOps expertise
- Demonstrate practical knowledge of cloud-native tooling
- Provide a deployable reference for interviews, portfolios, and learning


## 📄 License & Attribution
This project is based on the open-source microservices architecture from the [GoogleCloudPlatform/microservices-demo](https://github.com/GoogleCloudPlatform/microservices-demo) repository, licensed under the Apache 2.0 License.

Make sure to review the license terms and keep this attribution when using the code.
