# setup
Initial setup scripts for ubuntu+bash dev env
---

## Before cloning the repo
- [ ] desired: ensure *git* is installed
- [ ] desired: setup SSH keys 

## Clone
```
git clone git@github.com:sv-pro/setup.git
```

## Setup

### Git 
```
git config --global user.name "Sergey Vlasov"
git config --global user.email sergeyvlasov.pro@gmail.com
```

### VS Code

- [ ] install on the local machine
- [ ] extensions
    - [ ] Markdown Preview Enhanced
    - [ ] Remote Development

### Task-specific setup procedures

#### Local Machines
- Control plane machine
    - Terraform
    - Cloud (AWS/GCP/Azure/DO) SDK
    - Ansible
    - secrets mgmt
- Dev Env
    - VS Code
    - DL
        - Anaconda
        - Jupyter
#### Remote Machines
Ephemeral envs

- **Portfolio**
    - **cost awareness**
    - **automatic teardown**
- Dev Env
    - VS Code
    - Jupyter
        - Notebook
        - Lab
        - Hub
- Build/integration 
- Testing
- ML/DL
- Telegram bot

Persistent envs
- Database
- File/object storage
- Email/DNS etc. servers
    
