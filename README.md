# Sample Repository for ArgoCD Usage with Kustomize, Helm, and Nginx Proxy

This repository serves as a demonstration of how to use ArgoCD for continuous delivery and deployment, showcasing various usage examples including standard ArgoCD YAML usage, integration with Kustomize and Helm, and configuration of an Nginx proxy for DMZ cluster setup.

## Usage Examples

### Standard ArgoCD YAML Usage

In the `argocd` directory, you can find examples of standard ArgoCD YAML files for deploying applications to Kubernetes clusters. These YAML files define applications, their associated resources, and sync policies.

### Kustomize Usage

The `kustomize` directory contains examples of using Kustomize with ArgoCD. Kustomize allows for customization of Kubernetes manifests without directly modifying them. These examples demonstrate how to use Kustomize overlays for different environments or configurations.

### Helm Usage

In the `helm` directory, you'll find examples of using Helm charts with ArgoCD. Helm provides a package manager for Kubernetes applications, simplifying the deployment process. These examples showcase how to define Helm charts and values files for ArgoCD deployments.

### Nginx Proxy for DMZ Cluster

The `nginx-proxy` directory includes an example of configuring an Nginx proxy for a DMZ cluster setup. This demonstrates how to route traffic from external networks to internal Kubernetes services securely using Nginx.

## Getting Started

To get started with this repository, you'll need:

1. An existing Kubernetes cluster.
2. ArgoCD installed and configured in your Kubernetes cluster.
3. Helm and/or Kustomize installed locally for managing application configurations.

Follow the instructions in each directory's README.md file for detailed usage and deployment instructions.

## Contributing

Contributions to this repository are welcome! If you have any improvements or additional examples to add, feel free to fork this repository and submit a pull request.

## License

This repository is licensed under the [MIT License](LICENSE).
