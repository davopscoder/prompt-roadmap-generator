# Python, Terraform, Kubernetes, Helm Roadmap – 12 Weeks

## Phase 1: DevOps and Python Fundamentals
**Phase Objective:** Understand basic DevOps concepts and master Python for initial automation.

### Week 1 (Week 1 of Phase 1)
**Topic:** Introduction to DevOps and Python
**Objective:** Understand DevOps principles and set up a Python environment.

**Contents:**
- DevOps Principles
- Software Lifecycle
- Introduction to Python
- Installing Python and VSCode
- Version Control with Git
**Practice:**
- Setting Up a Python and Git Environment
- Creating Basic Scripts
- Using Remote Repositories
**Projects:**
1) Script that Prints System Status
**Review:** Script Review and Environment Setup
**Tags:** devops, python, fundamentals

### Week 2 (Week 2 of Phase 1)
**Topic:** Python for Automation
**Objective:** Write Python scripts for repetitive tasks.
**Contents:**
- Python syntax
- File handling
- Standard libraries
- Virtualenv
**Practice:**
- Creating a script that reads and writes files
- Using argparse
**Projects:**
1) Script to clean up old logs
**Review:** Code review and best practices
**Tags:** python, automation

## Phase 2: Infrastructure as Code Fundamentals
**Phase Objective:** Understand Terraform and IaC principles.

### Week 3 (Week 1 of Phase 2)
**Topic:** Introduction to Terraform
**Objective:** Understand IaC and configure a Terraform environment.
**Contents:**
- IaC Concepts
- Terraform Installation
- Providers and Basic Resources
**Practice:**
- Creating a Simple VM Configuration
- Deploying and Destroying Infrastructure
**Projects:**
1) Minimal On-Premises Cloud Infrastructure
**Review:** Validating Deployment and Controlled Destruction
**Tags:** terraform, iac

### Week 4 (Week 2 of Phase 2)
**Topic:** Variables and Modules in Terraform
**Objective:** Modularize infrastructure for reuse.
**Contents:**
- Variables and outputs
- Local and remote modules
- Best practices
**Practice:**
- Refactoring infrastructure using modules
- Adding configuration variables
**Projects:**
1) Modular infrastructure with network and server
**Review:** Modular structure review
**Tags:** terraform, modules

## Phase 3: Containers with Docker and Kubernetes
**Phase objective:** Learn how to deploy and manage containerized applications and Kubernetes.

### Week 5 (Week 1 of Phase 3)
**Topic:** Introduction to Docker and Kubernetes
**Objective:** Create Docker images and understand basic Kubernetes.

**Contents:**
- Dockerfile
- Docker build / run
- Pods and Deployments in Kubernetes
**Practice:**
- Create a Docker image for a Python app
- Deploy a pod in minikube
**Projects:**
1) Python app in Docker and a pod
**Review:** Validate the image and pod are working
**Tags:** Docker, Kubernetes

### Week 6 (Week 2 of Phase 3)
**Topic:** Services and volumes
**Objective:** Expose apps and manage persistent data.
**Contents:**
- Services and Types
- Persistent Volumes
- ConfigMaps and Secrets
**Practice:**
- Exposing an App with LoadBalancer
- Adding PVs and PVCs
**Projects:**
1) App with a Database and Persistent Volume
**Review:** Connectivity and Persistence Review
**Tags:** Kubernetes, Services

## Phase 4: Managing Deployments with Helm
**Phase Objective:** Deploy and manage Kubernetes packages with Helm.

### Week 7 (Week 1 of Phase 4)
**Topic:** Introduction to Helm
**Objective:** Install and use Helm for simple deployments.

**Contents:**
- Installing Helm
- Basic Charts
- helm install / upgrade
**Practice:**
- Creating a basic chart for a Python app
**Projects:**
1) Helm Chart for an existing app
**Review:** Validate deployment with Helm
**Tags:** helm, kubernetes

### Week 8 (Week 2 of Phase 4)
**Topic:** Advanced Helm and Repositories
**Objective:** Manage repositories and dynamic values.
**Contents:**
- Helm repo
- Advanced values.yaml
- Templates and helpers
**Practice:**
- Customizing deployment with values
- Using conditionals in templates
**Projects:**
1) Chart with configurable parameters
**Review:** Parameterization review
**Tags:** Helm, templates

## Phase 5: CI/CD with GitHub Actions
**Phase objective:** Automate testing and deployments with CI/CD pipelines.

### Week 9 (Week 1 of Phase 5)
**Topic:** Introduction to CI/CD
**Objective:** Configure a basic pipeline in GitHub Actions.

**Contents:**
- YAML workflows
- Jobs and steps
- Predefined actions
**Practice:**
- Pipeline for running Python tests
**Projects:**
1) Basic CI for validating code
**Review:** Actions execution review
**Tags:** cicd, github-actions

### Week 10 (Week 2 of Phase 5)
**Topic:** Automated Deployment
**Objective:** Integrate Terraform and Kubernetes in CI/CD.
**Contents:**
- Secrets on GitHub
- Terraform apply
- kubectl in pipelines
**Practice:**
- Pipeline that deploys infrastructure and app
**Projects:**
1) CD for a Python app
**Review:** Validate automated deployment
**Tags:** cicd, deployment

## Phase 6: DevOps Integration Project
**Phase objective:** Develop and deploy a complete solution with the tools learned.

### Week 11 (Week 1 of Phase 6)
**Topic:** Project Design
**Objective:** Plan the architecture and stack of the integration project.
**Contents:**
- Requirements definition
- Architecture diagrams
- Technology selection
**Practice:**
- Create project plan and backlog
**Projects:**
1) Design document and backlog
**Review:** Plan and scope review
**Tags:** project, architecture

### Week 12 (Week 2 of Phase 6)
**Topic:** Implementation and delivery
**Objective:** Implement, test, and deliver the integrative project.
**Contents:**
- Feature development
- Infrastructure as code
- CI/CD and monitoring
**Practice:**
- Deploy project in a live environment
**Projects:**
1) Final project deployed
**Review:** Final demo and feedback
**Tags:** project, final-delivery
