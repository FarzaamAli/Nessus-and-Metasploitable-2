## Preforming Vulnerability scan on Metasploitable-2 <br>
Welcome to the repository for "Vulnerablility Management using Nesus". This repository contains a PDF guide with step-by-step instructions on setting up and using Nessus for vulnerability management.

## Overview :bar_chart:

### What is Nessus? <br>
Nessus is a platform developed by Tenable that scans for security vulnerabilities in devices, applications, operating systems, cloud services and other network resources.

Nessus encompasses several products that automate point-in-time vulnerability assessments of a network's attack surface, with the goal of enabling enterprise IT teams to stay ahead of cyber attackers by proactively identifying and fixing vulnerabilities as the tool discovers them, rather than after attackers exploit them.
Nessus identifies software flaws, missing patches, malware, denial-of-service vulnerabilities, default passwords and misconfiguration errors, among other potential flaws. When Nessus discovers vulnerabilities, it issues an alert that IT teams can then investigate and determine what -- if any -- further action is required. <br>



### This guide covers:
- Setting up Metasploitable-2 assuming it as vulnerable machine :desktop_computer:
- Installing Nessus on Kali Linux :computer:
- Configuring Nessus for vulnerability scanning :gear:
- Performing a basic network scan :globe_with_meridians:
- Analyzing scan results :mag_right:
- Generating vulnerability reports :memo:

## Linux Commands :penguin:

Here are some of the Linux commands you'll use:

### Installing Nessus :package:
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

