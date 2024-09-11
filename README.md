# Hello World Helm Chart

This repository contains a simple Helm chart called `hello-world` that deploys an Nginx web server on a Kubernetes cluster. The chart is designed to run a basic "Hello World" application and serves as an example for learning how to use Helm with Kubernetes.

## Features
- **Nginx Deployment**: Deploys a single Nginx instance as a web server.
- **NodePort Service**: Exposes the service via NodePort for external access.
- **Configurable**: Easily customizable via the `values.yaml` file for various deployment scenarios.
- **Lightweight**: Suitable for testing Helm in local environments such as Minikube.

## Prerequisites
- Helm 3.x or later
- Minikube (or any Kubernetes cluster)
