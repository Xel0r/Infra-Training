# Infra-Training

**Demonstrates an end-to-end workflow using Terraform and Ansible to provision AWS servers and deploy multiple services.**

---

## Table of Contents

- [Overview](#overview)  
- [Technologies](#technologies)  
- [Setup](#setup)  
- [Usage](#usage)  
- [License](#license)

---

## Overview

This repository showcases a practical workflow for Infrastructure-as-Code (IaC) using **Terraform** and **Ansible**. It provisions AWS servers and deploys a variety of services, including:

- Docker  
- Nexus  
- Nginx  
- Node.js application  

It serves as a learning example for automating cloud infrastructure and application deployment.

---

## Technologies

- **Terraform** – Infrastructure provisioning  
- **Ansible** – Configuration management and service deployment  
- **AWS** – Cloud environment  
- **Docker** – Containerized applications  
- **Nexus** – Artifact repository  
- **Nginx** – Web server  
- **Node.js** – Sample application

---

## Setup

1. **Clone the repository**
```bash
git clone git@github.com:Xel0r/Infra-Training.git
cd Infra-Training
```

2. **Terraform**
```bash
cd terraform
terraform init
terraform apply
```

3. **Ansible**
```bash
cd ../ansible
ansible-playbook -i inventory main.yml
```

---

## Usage

- After running the Terraform and Ansible workflows, your AWS servers will be provisioned with all services deployed.  
- Access your services via the public IPs of the provisioned instances.

