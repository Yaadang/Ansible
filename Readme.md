# Ansible Bootcamp Project
This repository covers several automation and deployment projects. Below are detailed summaries of each project series.

## Automate Node App Deployment
### Accomplishments:
-Executed demos showcasing Node.js app deployment.\
-Created and configured DigitalOcean Droplets for hosting.\
-Wrote Ansible Plays for Node and npm installation, and for deploying Node.js apps.\
-Enhanced the deployment play and created a new Linux user for Node apps.
### Repository: Node Project
### Modules Used:
Copy, Unarchive, Npm, Command, User
## Automate Nexus Deployment
### Accomplishments:
-Created DigitalOcean Droplets for hosting Nexus. \
-Wrote Ansible Plays for Java and net-tools installation, downloading and unpacking Nexus, creating Nexus user, and starting Nexus.\
-Verified Nexus running.
### Modules Used:
-Get URL, Find, Group, File
## Configure Git & Default Inventory Location
Accomplishments:
Configured Git settings.
Set up default inventory location.
Ansible & Docker Integration
Accomplishments:
-Created EC2 Instance with Terraform and adjusted hosts inventory file.\
-Installed Python3, Docker, docker-compose, and started Docker daemon.\
-Added ec2-user to Docker group, and refactored the Playbook.\
-Adjusted plays, tested Docker pull, started Docker containers, and made the playbook more general-purpose.\
### Useful Links:
- Git Repo from Terraform Module (/Yaadang/Terraform)\
- Install docker-compose
### Modules Used:
- Yum, Pipe lookup, Systemd, Meta, Docker Image, Pip, Docker Login, Docker Compose
## Further Projects
### Ansible Integration in Terraform
### Dynamic Inventory
### Automate Kubernetes Deployment
### Ansible Integration in Jenkins 
### Ansible Roles
## Contributing
Feel free to fork the project and submit pull requests or raise issues. Follow the usual Git flow.
