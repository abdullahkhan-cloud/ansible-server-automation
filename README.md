# Automated Linux Server Configuration using Ansible

## Project Overview

This project automates the configuration of a Linux server using Ansible.

The playbook performs the following tasks:

- Installs Nginx
- Starts the Nginx service
- Enables Nginx on boot
- Deploys a custom index.html page

## Tools Used

- Ansible
- Ubuntu Linux
- AWS EC2
- SSH
- Git
- GitHub

## Project Structure

```
ansible-server-automation/
├── ansible.cfg
├── inventory.ini
├── playbook.yml
├── README.md
└── files/
    └── index.html
```

## Run the Playbook

```bash
ansible-playbook playbook.yml
```

## Skills Demonstrated

- Configuration Management
- Infrastructure Automation
- Linux Administration
- YAML
- SSH
- Ansible