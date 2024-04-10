# Kubernetes Stack for Amazon EKS

This repository contains a Kubernetes stack configured for Amazon Elastic Kubernetes Service (EKS). It includes configurations and scripts to deploy various components commonly used in Kubernetes applications.

## Components Included

- **Deployment Scripts**: Scripts for deploying the Kubernetes stack on Amazon EKS.
- **Sample Applications**: Sample applications to demonstrate the functionality of the Kubernetes cluster.
- **Configuration Files**: YAML files for configuring Kubernetes resources such as deployments, services, and ingresses.

## Prerequisites

- AWS CLI installed and configured with necessary permissions.
- kubectl installed and configured to connect to your Amazon EKS cluster.
- Terraform installed for managing infrastructure resources.

## Getting Started

1. Clone this repository:

```bash
git clone https://github.com/j-barak/KubernetesStackEKS.git
cd KubernetesStackEKS
```
2. Modify the configuration files as per your requirements.
3. Run the deployment scripts to provision the Kubernetes cluster:
```bash
./deploy.sh
```
4. Deploy your applications using kubectl or Helm.
