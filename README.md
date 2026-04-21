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

# 🔐 Kubernetes RBAC

This repository demonstrates how to implement **Role-Based Access Control (RBAC)** in Kubernetes using YAML manifests.

RBAC is a critical security feature in Kubernetes that helps control access to cluster resources based on roles assigned to users, groups, or service accounts.


## 📌 What is RBAC?

RBAC (Role-Based Access Control) is used to define:
- **Who** can access Kubernetes resources  
- **What actions** they can perform  
- **Where** those permissions apply  

It ensures secure and controlled access to your Kubernetes cluster.


## ⚙️ RBAC Components

### Role
Defines permissions within a specific namespace.

### ClusterRole
Defines permissions at the cluster level (across all namespaces).

### RoleBinding
Grants a Role to a user, group, or service account within a namespace.

### ClusterRoleBinding
Grants a ClusterRole across the entire cluster.


## Repository Structure
```
kubernetes-RBAC/
│── role.yaml
│── rolebinding.yaml
│── clusterrole.yaml
│── clusterrolebinding.yaml
│── serviceaccount.yaml
```
