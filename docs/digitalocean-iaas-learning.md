# DigitalOcean IaaS – Hands-on Learning

## Project Overview

This exercise focused on provisioning a cloud server using DigitalOcean, configuring its networking and security, preparing an Ubuntu environment, and hosting a Node.js application.

## 1. DigitalOcean Account and Droplet Creation
- Created a DigitalOcean account.
- Provisioned an Ubuntu Droplet.
- Selected CPU, RAM and SSD storage resources.
- Obtained the Droplet's public and private IP addresses.

## 2. Networking and Firewall Configuration
- Learned the purpose of public and private IP addresses.
- Configured an inbound firewall rule.
- Allowed SSH traffic through TCP port 22.
- Understood how firewall rules control access to cloud resources.

## 3. SSH and Linux User Management
- Generated an SSH key pair.
- Configured SSH authentication.
- Connected to the Droplet from a local Ubuntu environment.
- Explored root and regular Linux users.
- Created a separate deployment user and configured its SSH access.

## 4. Server Preparation
- Inspected CPU, RAM and disk resources.
- Installed Git.
- Installed Node.js.
- Verified npm installation.

## 5. Application Deployment
- Connected the Droplet to a GitHub repository.
- Cloned the Node.js application.
- Inspected package.json and package-lock.json.
- Installed application dependencies using npm.
- Explored running the Express application in detached mode using nohup.

## 6. Cost Optimization
- Learned the difference between stopping an application, powering off a Droplet and destroying a Droplet.
- Understood that powering off a Droplet does not necessarily stop billing.
- Explored resource management and avoiding unnecessary cloud expenses.

## Key Technologies
- DigitalOcean
- Ubuntu Linux
- SSH
- Git and GitHub
- Node.js
- npm
- Express.js
- Linux Firewall (UFW)
- Cloud Firewall

## Key Learning Outcome

Gained practical experience provisioning and configuring cloud infrastructure, securing remote access, managing Linux users, installing application dependencies and preparing a Node.js application for deployment.

This exercise provided a practical introduction to Infrastructure as a Service (IaaS) and the responsibilities involved in managing cloud-hosted applications.
