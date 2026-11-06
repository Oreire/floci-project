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


# Amendment

Yes. The previous README was written to reflect the target state of the platform. Based on what you've actually implemented so far, it would overstate your achievements in an interview.

A recruiter or panel will respect a README that accurately distinguishes between implemented, partially implemented, and planned capabilities.

FLOCI Project
Fake Local Cloud Infrastructure (FLOCI)
Overview

I created FLOCI (Fake Local Cloud Infrastructure) as a practical platform engineering project to emulate the structure and operating model of a cloud-native application platform using local infrastructure and open-source technologies.

The project provides a foundation for deploying containerised applications using Infrastructure as Code, Kubernetes, CI/CD and GitOps principles without incurring public cloud costs. At its current stage, the project focuses on repository structuring, version control, Kubernetes deployment preparation and infrastructure automation readiness.

Project Objectives

The objectives of this project are to:

Build a cloud-inspired local platform environment
Manage application, infrastructure and Kubernetes resources as code
Apply modern Git and GitHub workflows
Establish a foundation for Infrastructure as Code
Prepare for Kubernetes-based application deployments
Enable future CI/CD and GitOps implementation
Demonstrate platform engineering and DevOps best practices
Current Implementation Status
Capability	StatusGit Repository Management	✅ Implemented
GitHub Remote Repository	✅ Implemented
Repository Structure Design	✅ Implemented
Infrastructure as Code Directory Structure	✅ Implemented
Kubernetes Manifest Organisation	✅ Implemented
Local Development Environment (WSL)	✅ Implemented
CI/CD Pipeline	⏳ Planned
Docker Image Build Automation	⏳ Planned
GitHub Actions Workflow	⏳ Planned
Kubernetes Cluster Deployment	⏳ Planned
Argo CD GitOps Deployment	⏳ Planned
Terraform Infrastructure Provisioning	⏳ Planned
Technologies Used
Version Control
Git
GitHub
Development Environment
Ubuntu on WSL
Visual Studio Code
Platform Engineering
Kubernetes (manifests in development)
Terraform (infrastructure definitions in development)
Planned Technologies
Docker
GitHub Actions
GitHub Container Registry (GHCR)
KIND
Argo CD
Ingress-NGINX
Repository Structure
floci-project
│
├── app/
│   └── Application resources
│
├── kube/
│   └── Kubernetes manifests
│
├── terra/
│   └── Terraform configurations
│
├── .gitignore
│
└── README.md

Work Completed
Repository Establishment

I successfully:

Initialised a local Git repository.
Configured the repository to use the main branch.
Created and managed a GitHub remote repository.
Resolved repository synchronisation issues between local and remote histories.
Configured branch tracking between local and remote repositories.
Pushed the repository contents to GitHub.

Example commands used:

git init
git branch -m main
git remote add origin https://github.com/Oreire/floci-project.git
git pull origin main --allow-unrelated-histories --no-rebase
git push -u origin main

GitHub Integration

I integrated the project with GitHub and addressed several practical source control challenges, including:

Repository creation and initialisation
Remote configuration
Merging divergent repository histories
Branch management
Upstream tracking configuration

These activities closely mirror everyday tasks performed within engineering teams.

Platform Structure Design

I established a clear separation of concerns by organising the repository into dedicated areas for:

Application Components
app/


Reserved for application source code and deployment artefacts.

Kubernetes Resources
kube/


Reserved for deployment manifests and cluster configuration.

Infrastructure as Code
terra/


Reserved for Terraform-managed infrastructure definitions.

This structure follows industry best practice by separating application, platform and infrastructure responsibilities.

Engineering Principles Applied
Everything as Code

The project is structured so that future application, infrastructure and deployment configurations can be maintained through version control.

Source Control First

All platform artefacts are intended to be versioned, audited and reviewed through Git workflows.

Separation of Concerns

Application code, Kubernetes configuration and infrastructure code are maintained independently to improve maintainability and scalability.

Reusable Foundations

The repository structure has been intentionally designed to support future automation and platform growth.

Key Challenges Overcome

During the project I successfully resolved:

Git repository initialisation issues
GitHub remote repository configuration
Repository history reconciliation
Branch tracking configuration
Authentication and repository access validation
WSL-based development environment usage

These are common operational challenges encountered in real development and platform engineering environments.

Key Outcomes

✅ Established and configured a GitHub-hosted repository

✅ Implemented a maintainable project structure

✅ Created dedicated areas for application, Kubernetes and Terraform resources

✅ Applied industry-standard Git workflows

✅ Established a platform foundation suitable for future CI/CD implementation

✅ Prepared the repository for future Kubernetes and Infrastructure as Code development

Planned Next Steps
Phase 1
Create Terraform infrastructure definitions
Develop application resources within app/
Create Kubernetes deployment manifests
Phase 2
Build and containerise the application using Docker
Store images in GitHub Container Registry (GHCR)
Implement GitHub Actions workflows
Phase 3
Deploy workloads to a local KIND cluster
Add automated deployment validation
Introduce GitOps practices using Argo CD
Phase 4
Add monitoring, observability and platform security controls
Implement ingress management and TLS
Extend the platform towards a production-style architecture
Recruiter Summary

This project demonstrates my practical understanding of Git, GitHub, repository management, Infrastructure as Code principles and Kubernetes-oriented platform design. While the platform is currently at the foundation stage, it has been deliberately structured to support the implementation of CI/CD, Kubernetes deployments, containerisation and GitOps workflows. The work completed so far reflects the initial phases of building a modern cloud-native platform using industry-standard engineering practices.
