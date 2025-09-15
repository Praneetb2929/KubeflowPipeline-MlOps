# Kubeflow Pipelines: Zero to Hero with Realtime MLOps Project

This project demonstrates how to build and run **Kubeflow Pipelines (KFP)** using real examples, from installation to running ML pipelines in a Kubernetes environment.

---

## 🚀 Project Overview

Kubeflow Pipelines (KFP) allow building reproducible and scalable ML workflows on Kubernetes.  
This project includes two example pipelines:
1. A simple **Hello World pipeline** to demonstrate the KFP setup.
2. A real-world **Iris classification pipeline** that loads data, trains a model, and outputs accuracy.

---

## ✅ Prerequisites

- Docker Desktop installed  
  [Install Docker Desktop](https://docs.docker.com/desktop/setup/install/mac-install/)

- KIND (Kubernetes in Docker) for local cluster setup  
  [Install KIND](https://kind.sigs.k8s.io/docs/user/quick-start/)

- Kubeflow Pipelines Operator installed on Kubernetes  
  [Install KFP](https://www.kubeflow.org/docs/components/pipelines/operator-guides/installation/)

---

## ⚡ Installation & Setup

1. Create project directory  
   ```bash
   mkdir kfp_project && cd kfp_project
2. Set up Python virtual environment
   ```bash
   python3 -m venv .kfp_env
   source .kfp_env/bin/activate
3. Install KFP Python SDK
   ```bash
   pip install kfp==2.9.0
4. (Optional) Install additional dependencies
   ```bash
   pip install -r requirements.txt
   
