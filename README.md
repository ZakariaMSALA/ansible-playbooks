# ⚙️ Ansible Playbooks

This repository contains example Ansible playbooks for automating server configuration and application deployment.

## 📁 Project Structure

```
ansible-playbooks/
├── playbooks/
│   ├── setup_webserver.yml
│   └── harden_ssh.yml
├── inventory/
│   └── hosts.ini
```

## 🔧 Playbook Descriptions

### ✅ setup_webserver.yml
Installs and configures Nginx on a remote host.

### 🔒 harden_ssh.yml
Disables root login and enforces key-based authentication on SSH.

## ▶️ How to Run

1. Make sure you have Ansible installed:
```bash
ansible --version
```

2. Update the `inventory/hosts.ini` file with your remote server's IP.

3. Run a playbook:
```bash
ansible-playbook -i inventory/hosts.ini playbooks/setup_webserver.yml
```

## 📬 Author

Zakaria Msala – Freelance DevOps Engineer  
[LinkedIn](https://linkedin.com/in/zakaria-msala)
