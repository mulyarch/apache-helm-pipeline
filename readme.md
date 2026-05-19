# Apache Helm Pipeline

![CI](https://github.com/YOUR_USERNAME/apache-helm-pipeline/actions/workflows/ci.yml/badge.svg)
![Infrastructure](https://github.com/YOUR_USERNAME/apache-helm-pipeline/actions/workflows/deploy-infra.yml/badge.svg)
![Deploy](https://github.com/YOUR_USERNAME/apache-helm-pipeline/actions/workflows/deploy-app.yml/badge.svg)

## Overview
Full CI/CD pipeline deploying Apache web server on AWS EKS using Docker, Terraform, Ansible, Helm, and GitHub Actions.

## Tech Stack
- **Docker** — Containerized Apache web server
- **Terraform** — AWS infrastructure (VPC, EKS, IAM)
- **Ansible** — Cluster configuration and deployment orchestration
- **Helm** — Kubernetes manifest management
- **GitHub Actions** — CI/CD automation
- **AWS EKS** — Managed Kubernetes
- **AWS NLB** — Public Load Balancer
