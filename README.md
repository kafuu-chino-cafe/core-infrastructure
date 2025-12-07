# kafuu-chino.cafe / infra

This repository contains the infrastructure configuration for my homelab. It uses **Helmfile** to initialize GitOps controllers, which then synchronize the cluster state with this repository.

## Prerequisites

* **Kubectl** (configured for target cluster)
* **Helm** v3.8+ (OCI support required)
* **Helmfile** v0.140+
* **Helm Diff Plugin:**
    ```bash
    helm plugin install https://github.com/databus23/helm-diff
    ```

## Overview
The project still in early development, there are no public endpoints or diagrams yet.
