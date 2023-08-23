### Jenkins-Ansible Integration for AWS EC2 Configuration
## Overview

Set up a CI/CD pipeline with Jenkins and Ansible to automate the configuration of two AWS EC2 instances.

### Prerequisites:
    A dedicated server for Jenkins.
    A dedicated server for the Ansible Control Node.
    Two EC2 instances as Ansible Managed Nodes.

### Setup Steps:
1. Jenkins Server:

    Set up and configure a dedicated server for Jenkins.
    Install necessary Jenkins plugins:
        Pipeline
        SSH Agent
        SSH Steps
        Credentials
        Credentials Binding
    Add SSH key credentials for:
        Ansible Control Node server
        Ansible Managed Node servers (EC2)

2. Ansible Control Node:

    Set up and configure a dedicated server for the Ansible Control Node.
    Ensure the Ansible Control Node can connect to the EC2 instances via SSH.
    Static inventory file pointing to the two EC2 instances from the inventory_aws_ec2.yaml

3. Jenkinsfile:

The Jenkinsfile should automate the following:

    Connect to the Ansible Control Node.
    Transfer the Ansible playbook and associated configuration files from the ansible folder.
    Copy the SSH keys for the EC2 instances to the Ansible Control Node.
    Install Ansible, Python3, and Boto3 on the Ansible Control Node.
    Execute the Ansible playbook on the Control Node to configure the EC2 instances.

### Execution:
    After setting up, whenever changes are committed or the Jenkins job is triggered, Jenkins will automatically configure the two EC2 instances using Ansible.    