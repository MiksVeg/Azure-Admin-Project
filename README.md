# Project Title: Azure Website Deployment (Azure Admin Project)

## Overview
Welcome to the Azure Website Deployment project! This repository contains the necessary scripts and configurations to deploy a sophisticated website architecture for a corporate client using Microsoft Azure services. The project aims to optimize traffic distribution, enhance user experience, and ensure seamless connectivity across geographically dispersed regions.

## Project Goals
- Deploy a multi-page website consisting of a home page, an upload page connected to Azure Blob Storage, and custom error pages.
- Configure Application Gateway to efficiently route traffic based on user requests.
- Implement robust error handling mechanisms using static website hosting in Azure Containers.
- Establish secure and seamless connectivity between regions using VNet-VNet Peering.

## Technical Specifications
### Azure Services Utilized:
- Virtual Machines (VMs)
- Application Gateway
- Azure Blob Storage
- Traffic Manager
- Azure Containers

### Deployment Steps:
1. Clone the GitHub repository to all VMs.
2. Execute `vm1.sh` script on VM1 to deploy the upload page.
3. Execute `vm2.sh` script on VM2 to install the home page.
4. Update `config.py` file on VM1 with storage account details.
5. Run `sudo python3 app.py` command on VM1.
6. Establish VNet-VNet Peering between regions.
7. Configure Traffic Manager to point to Application Gateway in both regions.

## Key Achievements
- Successfully deployed a comprehensive website architecture meeting client requirements.
- Optimized traffic distribution and enhanced user experience.
- Implemented robust error handling mechanisms for seamless error management.
- Ensured secure and efficient connectivity between regions.

## Getting Started
To get started with the deployment process, follow the steps outlined in the [Deployment Guide](deployment_guide.md).

## Contributors
- [Soumik Mondal](https://www.linkedin.com/in/soumik-mondal/)
