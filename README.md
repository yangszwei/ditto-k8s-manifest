# ditto-k8s-manifest

This repository contains Kubernetes manifests to streamline the deployment of the DITTO systems.

## Prerequisites

Ensure you have the following installed before proceeding:

- [Kubernetes](https://kubernetes.io/docs/setup/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- A running Kubernetes cluster (e.g., Minikube, GKE, EKS)

## Building the Images

Build Docker images for each system as per the README files. The following instructions focus on building images for the current deployment.

## Deployment

To deploy the services to your Kubernetes cluster, run:

```shell
kubectl apply -R -f .
```
