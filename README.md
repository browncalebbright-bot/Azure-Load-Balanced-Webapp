# Azure Load-Balanced Web Application

## Project Overview

This project demonstrates the deployment of a highly available web application using Azure Virtual Machines and Azure Load Balancer.

The solution distributes incoming web traffic across multiple Linux virtual machines running NGINX, improving availability and fault tolerance.

---

## Architecture

Internet
↓
Azure Load Balancer
↓
Backend Pool
├── web1 (Linux VM)
└── web2 (Linux VM)

---

## Technologies Used

- Microsoft Azure
- Azure Virtual Network (VNet)
- Azure Network Security Groups (NSG)
- Azure Load Balancer
- Azure Virtual Machines
- Ubuntu Linux
- NGINX
- SSH

---

## Implementation Steps

1. Created a Virtual Network and Subnet
2. Deployed two Linux Virtual Machines
3. Configured NSG rules for HTTP and SSH access
4. Installed and configured NGINX on both VMs
5. Created an Azure Load Balancer
6. Added both VMs to the backend pool
7. Configured health probes
8. Configured load balancing rules
9. Tested traffic distribution across both servers

---

## Skills Demonstrated

- Azure Networking
- Virtual Machine Administration
- Linux Server Management
- Load Balancing
- Health Probes
- Network Security Groups
- NGINX Configuration
- Troubleshooting

---

## Outcome

Successfully deployed a load-balanced web application using Azure infrastructure and verified traffic distribution across multiple backend servers.
