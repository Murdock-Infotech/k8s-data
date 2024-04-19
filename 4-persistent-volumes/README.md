# 4-Persistent Volumes

This directory contains Kubernetes configurations related to Persistent Volumes and Persistent Volume Claims.

## Configuration List

- `deployment-with-pvc.yaml`: This is a Deployment configuration for a Redis server. It includes a PersistentVolumeClaim of 10GB for data persistence.

## Usage

To apply a configuration, use the following command:

```bash
kubectl apply -f deployment-with-pvc.yaml