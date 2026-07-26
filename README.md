# Automated Linux Server Configuration using Ansible

## Project Overview

## Architecture

```
Local Machine (WSL Ubuntu)
        │
        │ SSH
        ▼
AWS EC2 Ubuntu Server
        │
        ▼
 Ansible Playbook
        │
        ▼
Install & Configure Nginx
        │
        ▼
Custom Web Page
```

---

This project automates the configuration of an Ubuntu Linux server on AWS EC2 using Ansible.

The playbook performs the following tasks:

- Installs Nginx
- Starts the Nginx service
- Enables Nginx to start automatically on boot
- Deploys a custom index.html web page

The project demonstrates Infrastructure Automation and Configuration Management using Ansible.

---

## Tools Used

- AWS EC2
- Ubuntu Linux
- Ansible
- SSH
- Git
- GitHub
- Nginx
- YAML

---