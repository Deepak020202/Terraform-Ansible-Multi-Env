# 🌐 Multi-Environment Setup with Terraform & Ansible

🔗 **LinkedIn:** [https://www.linkedln.deepakpatel-devops](https://www.linkedln.deepakpatel-devops)

---

## 📘 1. Project Overview

This project demonstrates the design and deployment of a **multi-environment infrastructure** using:

- **Terraform** for infrastructure provisioning
- **Ansible** for configuration management  
- **Nginx** to host a static portfolio website

Three separate environments are set up:
- `dev` (Development)
- `stg` (Staging)
- `prod` (Production)

### 🧠 This setup ensures:
- 🚀 Faster onboarding of environments  
- 🧪 Consistent deployment pipelines  
- 🔧 Minimal manual intervention  
- 🧭 Clear environment segregation  

---

## 🧩 2. Project Architecture

The architecture enables a **DevOps Engineer** to manage and scale infrastructure from a central system, using:

- A single **Terraform module structure** to provision multiple environments  
- **Ansible inventory files** (`dev`, `stg`, `prod`) for executing targeted configurations  
- Independent configuration states for each environment to maintain **isolation and control**

📌 *See project diagram for visual reference (available in repo).*

---

## ⚙️ 3. Tech Stack Used

### 🔧 Infrastructure Provisioning
- **Terraform**
  - Declarative Infrastructure as Code (IaC)
  - Remote state support (optional)
  - Reusable module pattern

### 🧰 Configuration Management
- **Ansible**
  - Environment-specific inventory files
  - Role-based Nginx configuration
  - SSH-based orchestration

### 📦 Web Hosting
- **Nginx**
  - Serves static HTML portfolio
  - Managed via Ansible

### ☁️ Cloud Platform
- **AWS**
  - EC2 (`t2.micro`) instances per environment
  - Public IP access for testing

### 💻 Developer Environment
- **Ubuntu**
  - Git, Terraform, and Ansible installed
  - CLI-based operations

---

## ✅ 4. Conclusion

This project establishes a **modular, scalable, and environment-driven** infrastructure setup using **Terraform and Ansible**, following DevOps best practices.

### 🔍 Key Takeaways:
- Clear segregation and reproducibility across environments  
- All setup is defined and managed as code  
- Easily extensible with CI/CD pipelines, monitoring, TLS setup, and more

> This architecture is a solid foundation for modern web deployments and automation-first infrastructure management.
