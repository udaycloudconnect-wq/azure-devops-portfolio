# Azure Linux Web Hosting & DevOps Portfolio

## Project Overview
This project demonstrates hosting a custom portfolio website
on an Ubuntu Linux virtual machine running on Microsoft Azure.

## Architecture
Developer -> GitHub -> Azure VM -> Nginx -> Website

GitHub Actions CI/CD is planned as the next implementation phase.

## Technologies
- Microsoft Azure Virtual Machine
- Ubuntu Linux
- Nginx Web Server
- HTML
- Git and GitHub
- GitHub Actions (planned)

## Implemented Features
- Deployed a custom HTML portfolio website.
- Installed and configured Nginx on Ubuntu.
- Configured Azure networking to allow HTTP traffic.
- Managed website source code with Git.
- Committed and pushed project files to GitHub.
- Verified website access using the Azure VM public IP.

## Verification Commands

Check Nginx:

    sudo systemctl status nginx --no-pager

Test the website locally:

    curl -I http://localhost

## GitHub Repository
https://github.com/udaycloudconnect-wq/azure-devops-portfolio

## Planned Improvements
- GitHub Actions automated deployment.
- Secure SSH-based deployment.
- HTTPS with a valid TLS certificate.
- Deployment health checks and rollback.
- Improved monitoring and security.

## Learning Outcomes
- Azure VM administration
- Linux service management
- Nginx web hosting
- Git version control
- Azure network security rules
- CI/CD fundamentals

## Author
Uday Singh
