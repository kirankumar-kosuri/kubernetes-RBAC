# Kubernetes RBAC

This repository contains examples and configurations for implementing Role-Based Access Control (RBAC) in Kubernetes.

## What is RBAC?

RBAC (Role-Based Access Control) is a method used to control access to Kubernetes resources based on roles assigned to users or service accounts.

It helps in securing the cluster by defining:
- Who can access resources
- What actions they can perform

## Components Used

- Role → Defines permissions within a namespace
- ClusterRole → Defines cluster-wide permissions
- RoleBinding → Assigns a Role to a user/service account
- ClusterRoleBinding → Assigns a ClusterRole across the cluster

## Repository Contents

- YAML manifests for RBAC resources
- Examples for namespace-level and cluster-level access
- Sample configurations for learning and practice

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/kirankumar-kosuri/kubernetes-RBAC.git

It ensures secure and controlled access to your Kubernetes cluster.

## Repository Structure
```
kubernetes-RBAC/
│── role.yaml
│── rolebinding.yaml
│── clusterrole.yaml
│── clusterrolebinding.yaml
│── serviceaccount.yaml
```
