# 🔐 Keycloak Home Lab – Evelyn Madzanire

This repository documents my **Keycloak Identity and Access Management (IAM)** home lab setup.  
The goal of this project is to understand **user authentication, authorization, and role-based access control** using **Keycloak** and **Java**.

---

## 🧰 Tools & Technologies
- **Keycloak** (Open-source IAM tool)
- **Java JDK**
- **Windows OS**
- **Command Prompt / Terminal**
- **Web Browser** (for Admin Console)

---

## ⚙️ Project Overview
This lab demonstrates:
- Installation and setup of Keycloak
- Running Keycloak server
- Creating Realms, Roles, Groups, and Users
- Logging into the Admin Console
- Testing access control

---

## 🪜 Step-by-Step Process

### 🧩 Step 1: Install Java
- Installed **OpenJDK** and verified version  
- Configured **Environment Variables**  
![Java Installed](java-install.png)

---

### 🧩 Step 2: Download and Extract Keycloak
- Downloaded Keycloak from the official site  
- Extracted ZIP folder  
- Opened the `bin` directory  
![Keycloak Extracted](keycloak-extract.png)

---

### 🧩 Step 3: Run Keycloak Server
- Started Keycloak server using:
  ```bash
  kc.bat start-dev
