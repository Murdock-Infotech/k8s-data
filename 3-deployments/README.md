# 3-Deployments

This directory contains Kubernetes Deployment configurations.

A Kubernetes Deployment is a specification for one or more containers that will re-deploy automatically if a pod fails. By default a Deployment doesn’t have persistence. One use of a Deployment would be a Redis server. If you needed persistence with Redis, you could add a Persistent Volume to the Deployment. That is the example we use here.

## Deployment List

- `deployment.yaml`: This is a Deployment configuration for a Redis server. It includes a PersistentVolumeClaim of 10GB for data persistence.

## Usage

To apply a Deployment, use the following command:

```bash
kubectl apply -f deployment.yaml