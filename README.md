# 🕷️ WebShell-Arsenal  
### *Modular, Tactical Web Shell Collection for Red Teamers & Security Researchers*

---

## 🔥 About the Project

**WebShell-Arsenal** is a curated, **multi-purpose collection of web shells** crafted for offensive security, red teaming, and post-exploitation research. This repository features **minimalist, task-focused shells** for various tech stacks such as **PHP, WAR (Java), ASPX, JSP**, and others — each created to fulfill specific tactical objectives like:

- 🔍 **File Exploration**
- 🚪 **Privilege Escalation**
- 📦 **File Upload / Download**
- 🔄 **Reverse Shell / Callback**
- 🧬 **Payload Staging**
- 🧱 **Basic C2 Interaction**

This is an **open contribution project**, inviting community members to submit **clean, original, and task-specific web shells** for learning, simulation, and adversary emulation.

---

## 🧰 Tech Stack & Shell Types

Currently supported categories:

| Language / Platform | Shell Examples                          | Use Case                        |
|---------------------|------------------------------------------|----------------------------------|
| PHP                 | `php_cmd.php`, `php_filemgr.php`         | RCE, File Manager, Reverse Shell |
| WAR (Java)          | `war-shell.war`, `cmd.jsp`               | Apache Tomcat Exploits           |
| ASPX                | `aspx_exec.aspx`                         | RCE on IIS / Windows targets     |
| JSP                 | `jsp-console.jsp`                        | Java Web App Backdoor            |
| Shell Scripts       | `upload.sh`, `enum.sh`                   | Lateral Movement / Priv Esc      |
| PowerShell          | `ps-reverse.ps1`                         | Windows Post-Exploitation        |
| Others (TBD)        | Open for Python/NodeJS contributions     | Multi-Platform Payload Dev       |

> ⚠️ Every shell is **minimal**, **task-scoped**, and **annotated** for clarity.

---

## 📁 Repository Structure

```bash
WebShell-Arsenal/
│
├── PHP/
│   ├── php_reverse.php
│   ├── php_filemanager.php
│   └── ...
├── WAR/
│   ├── war_shell.war
│   ├── jsp_exec.jsp
│   └── ...
├── ASPX/
│   ├── shell.aspx
├── Scripts/
│   ├── priv_esc.sh
│   └── upload_enum.sh
├── PowerShell/
│   ├── reverse.ps1
├── CONTRIBUTING.md
├── README.md
└── LICENSE
