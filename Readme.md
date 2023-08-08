# Ansible Bootcamp Project
This repository covers several automation and deployment projects. Below are detailed summaries of each project series.

## Automate Node App Deployment
### Accomplishments:
- Executed demos showcasing Node.js app deployment.
- Created and configured DigitalOcean Droplets for hosting.
- Wrote Ansible Plays for Node and npm installation, and for deploying Node.js apps.
- Enhanced the deployment play and created a new Linux user for Node apps.
### Repository: Node Project
### Modules Used:
Copy, Unarchive, Npm, Command, User
## Automate Nexus Deployment
### Accomplishments:
- Created DigitalOcean Droplets for hosting Nexus. 
- Wrote Ansible Plays for Java and net-tools installation, downloading and unpacking Nexus, creating Nexus user, and starting Nexus.\
- Verified Nexus running.
### Modules Used:
-Get URL, Find, Group, File
## Ansible & Docker Integration
Accomplishments:
- Created EC2 Instance with Terraform and adjusted hosts inventory file.\
- Installed Python3, Docker, docker-compose, and started Docker daemon.\
- Added ec2-user to Docker group, and refactored the Playbook.\
- Adjusted plays, tested Docker pull, started Docker containers and made the playbook more general-purpose.\
### Useful Links:
- Git Repo from Terraform Module (/Yaadang/Terraform)
- Install docker-compose
### Modules Used:
- Yum, Pipe lookup, Systemd, Meta, Docker Image, Pip, Docker Login, Docker Compose

## Ansible Integration in Terraform
### Accomplishments:

- Executed a demonstration of Ansible integration with Terraform.
- Adjusted the Terraform configuration file to run the Ansible playbook.
- Developed a new Ansible Playbook specifically for Terraform integration.
- Wrote a Play titled "Wait for ssh connection".
- Incorporated the “null_resource” in the Terraform configuration file.

### Useful Links:
- Ansible part of the Terraform project (/Yaadang/Terraform)
- TF Provisioner
- TF Null Resource

### Modules Used:
- Wait For Module

## Dynamic Inventory
### Accomplishments:
- Executed a demo about Dynamic Inventory.
- Used Terraform to create EC2 Instances.
- Drafted a plugin configuration for aws_ec2.
- Modified the Terraform configuration for public DNS assignment.
- Tweaked Ansible playbook and ansible.cfg to leverage dynamic hosts from AWS.
- Added a fourth server and re-executed the Ansible playbook.
- Targeted only specific servers in your AWS region using filters and keyed_groups.
### Useful Links:
- Working with Dynamic Inventory
- Git Repo from Terraform Module
- Inventory Plugins
- EC2 Inventory Source
- Ansible-inventory command
## Automate Kubernetes Deployment
Accomplishments:
- Used Terraform to create a K8s cluster.
- Wrote a Play titled "Deploy app in new namespace".
- Set up the kubeconfig environment variable.
### Modules Used:
- K8s

## Ansible Integration in Jenkins
### Accomplishments:
- Executed a preparation demo for Ansible integration with Jenkins.
- Created a Droplet on DigitalOcean to serve as the Ansible Control Node.
- Set up the Droplet to function as the Ansible Control Node (including Ansible installation).
- Spawned 2 EC2 Instances for Ansible Managed Nodes.
- Conducted a demonstration on setting up a Jenkins Pipeline for Ansible integration.
- Installed the required Jenkins Plugins.
- Configured the credentials for the DigitalOcean Droplet (this includes Private Key for Ansible Server & EC2 Managed Servers).
- Scripted a Jenkinsfile.
- Established a Pipeline in Jenkins.
- Showcased optimizations in the integration of Ansible with Jenkins.

## Ansible Roles
### Accomplishments:
- Conducted a demonstration on Ansible Roles.
- Developed new roles.
- Incorporated the newly created roles in the Playbook.
- Created EC2 servers using Terraform.
- Executed the Ansible Playbook with the new roles.
### Useful Links:
- Official Documentation on Ansible Roles
- Variable Precedence in Ansible
## Contributing
Feel free to fork the project and submit pull requests or raise issues. Follow the usual Git flow.
