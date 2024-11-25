# Jenkins Installation Script for Ubuntu/Debian 20.04

This repository contains a Bash automation script to install Jenkins on Ubuntu/Debian 20.04 systems. The script handles Java installation, Jenkins repository setup, and service management.

---

## Features
- Fully automated Jenkins installation.
- Installs and configures Java (OpenJDK 11), a prerequisite for Jenkins.
- Adds Jenkins repository and installs Jenkins.
- Starts and enables the Jenkins service for auto-start on system boot.

---

## System Requirements
- **Operating System**: Ubuntu or Debian-based OS, version 20.04.
- **Hardware Requirements**:
  - Minimum 1GB RAM.
  - At least 1 CPU core.
- **Privileges**: Root or sudo access to the system.

---

## Usage

### Prerequisites
- Ensure your system meets the requirements listed above.
- Clone this repository to your machine:
  ```bash
  git clone https://github.com/ltsali8220/jenkins-installation-ubuntu.git
  cd jenkins-installation-ubuntu
