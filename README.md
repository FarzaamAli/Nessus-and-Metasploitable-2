# Nessus-and-Metasploitable-2
## Preforming Vulnerability scan on Metasploitable-2 <br>
Welcome to the repository for "Vulnerability Management with Nessus". This repository contains a PDF guide with step-by-step instructions on setting up and using Nessus for vulnerability management.

## Overview 📝

This guide covers:
- Setting up a vulnerable machine using Metasploitable2 💻
- Installing Nessus on Kali Linux 🐉
- Configuring Nessus for vulnerability scanning ⚙️
- Performing a basic network scan 🌐
- Analyzing scan results 🔍
- Generating vulnerability reports 📊

## Linux Commands 🐧💻

Here are some of the Linux commands you'll use:

### Installing Nessus 📦
```bash
sudo dpkg -i Nessus-10.8.1-debian10_amd64.deb
```
### Starting Nessus 🚀
```bash
systemctl start nessusd
```
### Accessing Nessus 🌐
Open your web browser and navigate to:
```bash
https://<System_IP>:8834/
```

