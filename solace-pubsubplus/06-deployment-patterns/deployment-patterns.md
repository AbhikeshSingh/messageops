# Solace PubSub+ Deployment Patterns

This guide covers common deployment strategies for Solace PubSub+ to help you choose the best fit for your environment.

## Deployment Environments

- **On-Premises:** Deploy Solace brokers on your own infrastructure for full control.
- **Cloud:** Use Solace managed services or deploy brokers in cloud platforms like AWS, Azure, or GCP.
- **Hybrid:** Combine on-prem and cloud deployments for flexibility and disaster recovery.
- **Containerized:** Run Solace brokers in containers (Docker, Kubernetes) for easy scaling and management.

## Common Patterns

- **Clustered Brokers:** Multiple brokers working as a cluster provide high availability and load balancing.
- **Network of Brokers:** Brokers interconnected across sites or clouds to enable global messaging and data distribution.
- **Edge Brokers:** Lightweight brokers deployed close to data sources or consumers for low latency and efficient routing.
- **Centralized Broker:** A single broker handles messaging traffic for smaller or less complex environments.

## Automation and Infrastructure as Code

Leverage tools like Ansible, Terraform, or Helm charts to automate deployment, configuration, and scaling, making operations repeatable and less error-prone.

Choosing the right pattern depends on your organization’s scale, reliability needs, and infrastructure capabilities.
