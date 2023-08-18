# Kubernetes Cluster Configuration with Ansible

This project automates the deployment and configuration of a Kubernetes cluster using Terraform and Ansible.

## Accomplishments

- **K8s Cluster Creation with Terraform**: Provisioned and set up a Kubernetes cluster using the infrastructure as code tool, Terraform.
- **Ansible Play for Deployment**: Authored an Ansible play titled "Deploy app in new namespace" to handle specific application deployment procedures.
- **Kubeconfig Environment Setup**: Properly configured the `kubeconfig` environment variable to manage cluster access and interactions.

## Prerequisites

- [Terraform](https://github.com/Yaadang/Terraform/tree/feature/eks)
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)

## Quick Start

1. **Terraform Setup**: Navigate to the Terraform directory in the link and run the following commands to initiate and apply the configuration:
   ```bash
   terraform init
   terraform apply
   ```
This will provision the Kubernetes cluster.

Kubeconfig Environment Setup: Ensure that the kubeconfig environment variable is set up to point to the appropriate configuration file.

   ```bash
    export KUBECONFIG=/path/to/kubeconfig
   ```
2 . **Run the Ansible Playbook**: Use the following command to run the Ansible play titled "Deploy app in new namespace":

   ```bash
     ansible-playbook deploy-app-playbook.yml
   ```

3. Ensure you have the appropriate inventory and hosts configured for Ansible to run the play
