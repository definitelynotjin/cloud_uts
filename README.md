# ☁️ PBL Cloud Architecture for CMLabs HRIS

This repository contains the implementation and planning for our PBL (Project-Based Learning) project using Microsoft Azure services. The project utilizes key components of cloud computing such as Virtual Machines, Virtual Cloud Networks, Cloud Storage, and DevOps pipelines.

---

## 📊 Cloud Architecture Diagram

The diagram below illustrates our cloud infrastructure setup:

![Cloud Architecture](./xsuit.png)

---

## ⚙️ Components Breakdown

| Component | Description |
|----------|-------------|
| **Virtual Machine (VM)** | Hosts the backend services or application server. |
| **Virtual Cloud Network (VCN)** | Provides secure internal communication between resources. |
| **Cloud Storage** | Used for storing user-generated files, backups, or static assets. |
| **Azure DevOps** | Enables CI/CD pipelines to automatically build, test, and deploy the app. |
| **Monitoring** | Azure Monitor or Log Analytics tracks app performance and usage. |
| **Users** | Access the application via HTTP/S endpoints through an App Gateway. |

---

## 🚀 DevOps Pipeline

1. **Repo (this repo)** stores the codebase.
2. **Pipelines**:
   - **Build Stage**: Validates and compiles the code.
   - **Deploy Stage**: Publishes to the Virtual Machine via Azure Pipeline agents.

---

## 📅 Timeline and To-Do

The full task breakdown and timeline can be found in our [Notion Board (https://www.notion.so/PBL-CMLabs-Kelompok-1-1df38d56ff688091a9a1d887aeec62d8?pvs=4).

---

