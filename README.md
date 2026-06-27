# Game Theory GitOps Repository

This repository contains Kubernetes deployment manifests for the Game Theory Backend.

Deployment is fully automated using:

- Jenkins (CI)
- Docker Hub
- Argo CD (GitOps)
- K3s Kubernetes

Any image tag update committed to this repository is automatically synchronized to the Kubernetes cluster by Argo CD.
