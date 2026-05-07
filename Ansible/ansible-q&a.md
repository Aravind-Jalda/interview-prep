# Ansible Interview Questions & Answers (DevOps - 2 to 5 Years)

---

## 1. What is Ansible?
Ansible is an open-source automation tool used for configuration management, application deployment, and orchestration.

---

## 2. Why Ansible is used in DevOps?
Ansible helps automate repetitive tasks like server setup, deployments, and configuration updates.

---

## 3. What is agentless architecture?
Ansible does not require any agent on target machines.  
It connects using SSH.

---

## 4. What is a playbook?
A playbook is a YAML file that defines automation tasks.

---

## 5. What is YAML?
YAML is a human-readable data format used in Ansible playbooks.

---

## 6. What is an inventory file?
Inventory file contains list of servers managed by Ansible.

---

## 7. What is a module in Ansible?
Modules are reusable units that perform tasks.  
Example: copy, yum, service

---

## 8. What is a role?
Role is a structured way to organize playbooks and tasks.

---

## 9. What is a task?
A task is a single action in a playbook.

---

## 10. What is handler?
Handler is a task that runs only when triggered.

---

## 11. What is idempotency?
Running the same playbook multiple times gives the same result without changes.

---

## 12. What is ansible.cfg?
Configuration file for Ansible settings.

---

## 13. What is a variable in Ansible?
Variables are used to store values and make playbooks dynamic.

---

## 14. What is loop in Ansible?
Used to repeat tasks.

---

## 15. What is template in Ansible?
Used to create dynamic files using Jinja2 templates.

---

## 16. What is ad-hoc command?
One-line command used for quick tasks.

Example:
ansible all -m ping

---

## 17. What is vault in Ansible?
Used to encrypt sensitive data.

---

## 18. What is fact gathering?
Ansible collects system information before running tasks.

---

## 19. How Ansible is used in DevOps?

- Server configuration  
- Application deployment  
- Automation  
- Orchestration  

---

## 20. Example workflow

Inventory → Playbook → Execute → Configure servers

---
