# floci-project
FLOCI DEPLOYMENT PROJECTS: AN EMULATION OF AWS CLOUD PLATFORM

FLOCI Project
Local Cloud Infrastructure Platform (FLOCI)

# Overview

I designed and implemented FLOCI (Fake Local Cloud Infrastructure) to emulate the capabilities and workflows of a modern cloud platform using locally hosted infrastructure and open-source tooling.

The objective was to build a production-inspired platform that demonstrates how containerised applications can be built, deployed, operated and managed using industry-standard DevOps, Platform Engineering and GitOps practices without incurring public cloud costs.

This project serves as a practical demonstration of skills across:

Cloud-native engineering
Kubernetes operations
Infrastructure as Code
Continuous Integration and Continuous Deployment (CI/CD)
GitOps
Containerisation
Platform Engineering
Developer Experience (DevEx)

# Project Objectives

The primary goals of the project were to:

Emulate a cloud platform locally
Deploy containerised applications in Kubernetes
Automate build and deployment workflows
Implement Infrastructure as Code principles
Demonstrate GitOps deployment patterns
Create a repeatable and reproducible development environment
Gain hands-on experience with production-style platform operations

# Architecture

GitHub Repository
        │
        ▼
GitHub Actions CI/CD
        │
        ▼
Container Build
        │
        ▼
GitHub Container Registry (GHCR)
        │
        ▼
Kubernetes Cluster (KIND)
        │
        ▼
Application Deployment
        │
        ▼
Ingress / Service Exposure


# Future enhancements include:

GitHub
   │
   ▼
Argo CD
   │
   ▼
Kubernetes Cluster
   │
   ▼
Automated GitOps Synchronisation

# Technologies at a Glance

Category	TechnologySource Control	Git, GitHub
CI/CD	GitHub Actions
Containerisation	Docker
Container Registry	GitHub Container Registry (GHCR)
Orchestration	Kubernetes
Local Kubernetes	KIND
GitOps	Argo CD (planned)
Infrastructure as Code	Terraform
Operating System	Ubuntu on WSL
Development Environment	Visual Studio Code
Networking	Kubernetes Services & Ingress
Automation	Self-Hosted GitHub Runner

# Repository Structure

floci-project
│
├── app/
│   └── Application source code
│
├── kube/
│   └── Kubernetes manifests
│
├── terra/
│   └── Terraform infrastructure code
│
├── .gitignore
│
└── README.md

# Key Activities Undertaken

1. Git Repository Creation and Management

I initialised a Git repository locally and established GitHub version control practices including:

Branch management
Commit history management
Remote repository integration
GitHub collaboration workflows

Example commands used:

git init
git branch -m main
git add .
git commit -m "Initial commit"
git push -u origin main

2. Source Control Integration with GitHub

I connected the local repository to GitHub and resolved common Git integration challenges including:

Remote repository configuration
History reconciliation
Divergent branch resolution
Repository synchronisation

This mirrored real-world scenarios frequently encountered by platform and DevOps engineers.

3. Kubernetes Platform Foundations

I structured the repository to support Kubernetes-based deployments through dedicated manifest management.

The platform design supports:

Deployments
Services
Ingress resources
Namespace management
Application scaling

This provides a clear separation between application code and operational infrastructure.

4. Infrastructure as Code

Infrastructure definitions were organised separately to support an Infrastructure as Code (IaC) approach using Terraform.

Benefits include:

Repeatable deployments
Environment standardisation
Reduced configuration drift
Improved operational consistency
5. CI/CD Readiness

The repository structure was designed to support the creation of automated delivery pipelines.

Planned pipeline stages include:

Source Code Commit
        │
        ▼
Build
        ▼
Test
        ▼
Containerise
        ▼
Push to GHCR
        ▼
Deploy to Kubernetes
        ▼
Verification


This aligns with modern DevOps delivery practices used across public and private sector organisations.

6. GitOps Readiness

The platform design intentionally supports future GitOps implementation using Argo CD.

# Planned capabilities include:

Declarative deployments
Continuous reconciliation
Drift detection
Automated synchronisation
Environment promotion

These approaches are increasingly common across cloud-native platforms and large-scale government environments.

# Engineering Principles Applied

# Infrastructure as Code

All infrastructure should be version-controlled, reproducible and auditable.

Automation First

Manual operational tasks should be reduced wherever possible through automation.

# Immutable Infrastructure

Application deployments should be achieved through versioned artefacts rather than direct server modifications.

# Declarative Configuration

Desired system states should be defined as code.

Git as the Single Source of Truth

Infrastructure and application changes should be traceable through source control.

# Challenges Addressed

During development I resolved several realistic platform engineering challenges including:

Git authentication issues
Repository history conflicts
Remote repository synchronisation
Branch management
WSL environment configuration
Development tooling integration
Repository structure design

These challenges provided practical experience similar to issues encountered in operational engineering teams.

# Key Outcomes

✅ Successfully established a cloud-inspired local platform environment

✅ Created a structured repository supporting application, infrastructure and Kubernetes resources

✅ Implemented GitHub integration and version-controlled workflows

✅ Prepared the foundation for Kubernetes deployment automation

✅ Established a platform architecture capable of supporting GitOps workflows

✅ Demonstrated practical understanding of containerisation, orchestration and infrastructure automation principles

✅ Produced a reusable foundation for future cloud-native deployments

# What I Would Implement Next

To further evolve the platform towards production standards, I would implement:

# Short-Term

GitHub Actions CI/CD pipelines
Docker image build automation
GitHub Container Registry integration
Self-hosted GitHub runners
KIND deployment automation

# Medium-Term

Argo CD GitOps deployment model
Ingress-NGINX controller
TLS certificate management
Secrets management
Helm-based deployments
# Long-Term

High availability Kubernetes clusters
Monitoring with Prometheus
Visualisation with Grafana
Centralised logging
Security scanning and compliance controls

# Project Summary

This project demonstrates practical capability across the cloud-native delivery lifecycle, from source control and infrastructure automation through to Kubernetes platform design and deployment automation. It showcases hands-on experience with technologies commonly used by modern Platform Engineering, Cloud Engineering and DevOps teams, while applying industry best practices such as Infrastructure as Code, GitOps, CI/CD and container orchestration.

The project provides evidence of my ability to build, automate and manage modern application platforms using open-source technologies in a cost-effective and repeatable manner.