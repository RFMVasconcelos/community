This is an initial proposal, to be iterated on, following the discussion in [#2293](https://github.com/kubeflow/website/issues/2293).

### Kubeflow documentation structure

- **Getting Started**
  - Introduction (current About/Kubeflow)
  - Overview (current Kubeflow Overview)
  - Use Cases (current About/Use Cases)
  - Installing Kubeflow
  - Cloud Installation
    - AWS
    - Azure
    - Google Cloud
    - IBM Cloud
  - Kubernetes installation
    - Overview of Deployment on Existing Clusters
    - Kubeflow Deployment with kfctl_k8s_istio
    - Multi-user, auth-enabled Kubeflow with kfctl_existing_arrikto
    - Multi-user, auth-enabled Kubeflow with kfctl_istio_dex
  - Workstation Installation
    - Kubeflow on Linux
    - Kubeflow on macOS
    - Kubeflow on Windows
    - MiniKF
    - Deploy using MiniKF on GCP
    - Deploying with minikube on a single node
    - Kubeflow on MicroK8s
    
- **Community**
  - About (current About/Community)
  - Contributing (current About/Contributing to Kubeflow + details on Working Groups)
  - Documentation (merge current About/Docs + About/Style Guide for Kubeflow docs)
  - Events (current About/Events Calendar)
  - Google Summer of Code (keep)
    
- **Components of Kubeflow**
  - Central Dashboard
    - Central Dashboard 
    - Registration Flow
  - Metadata
  - Jupyter Notebooks
  - Fairing 
    - Overview of Kubeflow Fairing
    - Install Kubeflow Fairing
    - Configure Kubeflow Fairing
    - Fairing on Azure
    - Fairing on GCP
    - Tutorials
    - Reference
  - Feature Store
    - Introduction to Feast
    - Getting started with Feast
  - Frameworks for Training
    - Chainer Training
    - MPI Training
    - MXNet Training
    - PyTorch Training
    - TensorFlow Training (TFJob)
  - Hyperparameter Tuning
    - Introduction to Katib
    - Getting started with Katib
    - Running an experiment
    - Katib Configuration Overview
    - Environment Variables for Katib Components
  - Pipelines
    - Pipelines
  - Tools for Serving
    - Overview
    - KFServing
    - Seldon Core Serving
    - BentoML
    - NVIDIA Triton Inference Server
    - TensorFlow Serving
    - TensorFlow Batch Prediction
  - Multi-Tenancy in Kubeflow
    - Introduction to Multi-user Isolation
    - Design for Multi-user Isolation
    - Getting Started with Multi-user Isolation
  - Miscellaneous
    - Nuclio functions
- **Jupyter Notebooks**
  - Overview of Jupyter Notebooks in Kubeflow
  - Set Up Your Notebooks
  - Create a Custom Jupyter Image
  - Submit Kubernetes Resources
  - Build a Docker Image on GCP
  - Troubleshooting Guide
- **Pipelines**
  - Pipelines Quickstart
  - Installing Pipelines
    - Installation Options for Kubeflow Pipelines
    - Kubeflow Pipelines Standalone Deployment
    - Deploying Kubeflow Pipelines on a local cluster
  - Understanding Pipelines
    - Overview of Kubeflow Pipelines
    - Introduction to the Pipelines Interfaces
    - Concepts
  - Building Pipelines with the SDK
    - Introduction to the Pipelines SDK
    - Install the Kubeflow Pipelines SDK
    - Build Components and Pipelines
    - Create Reusable Components
    - Building Python function-based components
    - Best Practices for Designing Components
    - Pipeline Parameters
    - Python Based Visualizations
    - Visualize Results in the Pipelines UI
    - Pipeline Metrics
    - DSL Static Type Checking
    - DSL Recursion
    - Using environment variables in pipelines
    - GCP-specific Uses of the SDK
    - Manipulate Kubernetes Resources as Part of a Pipeline
  - Multi-user Isolation for Pipelines
  - Caching
  - Upgrading
  - Samples and Tutorials
    - Using the Kubeflow Pipelines Benchmark Scripts
    - Using the Kubeflow Pipelines SDK
    - Experiment with the Kubeflow Pipelines API
    - Experiment with the Pipelines Samples
    - Run a Cloud-specific Pipelines Tutorial
  - Troubleshooting
  - Reference
    - Component Specification
    - Pipelines API Reference
    - Pipelines SDK Reference
- **Kubeflow on AWS**
  - Deployment
    - Install Kubeflow
    - Uninstall Kubeflow
  - Customizing Kubeflow on AWS
  - AWS IAM Role for Service Account
  - Logging
  - Private Access
  - Authentication and Authorization
  - Authentication using OIDC
  - Configure Kubeflow Pipelines on AWS
  - Custom Domain
  - Optimized Jupyter Notebooks on AWS
  - Storage Options
  - Configure External Database Using Amazon RDS
  - Troubleshooting Deployments on Amazon EKS
  - Kubeflow on AWS Features
  - End-to-end Kubeflow on AWS
- **Kubeflow on Azure**
  - Deployment
    - Install Kubeflow
    - Initial cluster setup for existing cluster
    - Uninstall Kubeflow
  - Authentication using OIDC in Azure
  - End-to-End Pipeline Example on Azure
  - Access Control for Azure Deployment
  - Troubleshooting Deployments on Azure AKS
- **Kubeflow on GCP**
  - Deploying Kubeflow
    - Set up a Google Cloud Project
    - Set up OAuth for Cloud IAP
    - Management cluster setup
    - Deploy using kubectl and kpt
    - Monitor Cloud IAP Setup
    - Delete using CLI
    - Features of Kubeflow on GCP
    - Deploy using UI
  - Kubeflow On-premises on Anthos GKE
  - Pipelines on GCP
    - Connecting to Kubeflow Pipelines on Google Cloud using the SDK
    - Authenticating Pipelines to GCP
    - Upgrading
    - Enabling GPU and TPU
    - Using Preemptible VMs and GPUs on GCP
  - Customizing Kubeflow on GKE
  - Using Your Own Domain
  - Authenticating Kubeflow to GCP
  - Using Cloud Filestore
  - Securing Your Clusters
  - Troubleshooting Deployments on GKE
  - Tutorial: End-to-end Kubeflow on GCP
  - Logging and monitoring
- **Kubeflow on IBM Cloud**
  - Deployment
    - Install Kubeflow
    - Securing the Kubeflow authentication with HTTPS
    - Uninstall Kubeflow
  - Create an IBM Cloud cluster
  - Initial cluster setup for existing cluster
  - Using IBM Cloud Container Registry (ICR)
  - Pipelines on IBM Cloud Kubernetes Service (IKS)
  - End-to-end Kubeflow on IBM Cloud
- **Kubeflow Operator**
  - Introduction
  - Installing Kubeflow Operator
  - Installing Kubeflow
  - Uninstalling Kubeflow
  - Uninstalling Kubeflow Operator
  - Troubleshooting
- **Kubeflow on OpenShift**
  - Install Kubeflow on OpenShift
  - Uninstall Kubeflow
- **Tutorials, Samples, and Shared Resources**
  - Kubeflow Samples
  - Codelabs, Workshops, and Tutorials
  - Blog Posts
  - Videos
  - Shared Resources and Components
- **Further Setup and Troubleshooting**
  - Configuring Kubeflow with kfctl and kustomize
  - Kubeflow On-prem in a Multi-node Kubernetes Cluster
  - Usage Reporting
  - Istio Usage in Kubeflow
  - Job Scheduling
  - Troubleshooting
  - Frequently Asked Questions
  - Support
  - Integrations
- **Upgrading Kubeflow** (to be removed)
- **Reference**
  - Reference Overview
  - Kubeflow Versioning Policies
  - Dockerfile Locations
  - Katib Reference
  - MPIJob Reference
  - Notebook CRD Reference
  - PyTorchJob Reference
  - TFJob Reference

