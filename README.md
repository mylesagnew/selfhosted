# My Self-Hosted Lab using Proxmox and Docker

This project sets up a versatile, private lab environment using **Proxmox** and **Docker**. It allows for simulating, developing, and testing various IT infrastructure scenarios with the power of virtualisation and containerization.

## Overview
The lab is hosted on **Proxmox VE**, an open-source virtualization platform that allows you to create and manage virtual machines (VMs) and containers. Within these VMs or containers, **Docker** is used to run containerized applications. 
This combination provides a modular and scalable lab environment that can be easily customized for testing and learning purposes.

## Key Features
- **Proxmox Virtualisation**: Run multiple VMs and LXC containers on a single physical server. Simulate different operating systems and network environments.
  
- **Docker Containers**: Docker containers are used within Proxmox-managed VMs or containers to host services and applications in isolated environments. Each container runs its own instance, enabling easy scaling and management.

- **Networking**: Utilize Proxmox's advanced networking features such as VLANs, bridges, and firewalls to simulate enterprise-grade network setups.

- **Resource Management**: Assign CPU, memory, and storage to individual VMs and containers for optimized performance and efficiency.

- **Scalability**: Proxmox and Docker are highly scalable. Add more VMs, containers, or nodes to the Proxmox cluster and scale Docker containers as needed.

- **Snapshot and Backup**: Use Proxmox’s snapshot and backup functionality to save and restore VM states, ideal for testing and experimentation.

- **Automation**: Automate the deployment and management of your lab using Docker Compose, Proxmox APIs, and CLI scripts.

## Use Cases
1. **Testing New Technologies**: Run different OS environments, applications, or services in isolated setups for testing or development.
  
2. **Learning and Certification**: Study for certifications such as Linux, Docker, or networking by creating custom test scenarios.

3. **CI/CD Pipelines**: Simulate DevOps processes by setting up continuous integration and deployment pipelines using Docker.

4. **Network Simulations**: Configure virtual networks within Proxmox and use Docker to simulate networking scenarios or microservices architecture.

## Benefits
- **Flexibility**: Easily create, manage, and tear down isolated environments for various use cases.
- **Cost-Effective**: Utilize open-source tools and your own hardware to simulate complex infrastructure.
- **Control**: Full control over the lab environment with advanced resource allocation, networking, and automation options.

---

### Requirements
- Suitable Hardware
- Proxmox VE installed on a physical server or virtual environment
- Docker installed on the VMs or containers within Proxmox

### How to Set Up
1. Install **Proxmox VE** on your physical server.
2. Create VMs or containers within Proxmox.
3. Install **Docker** inside the VMs or containers.
4. Deploy your desired applications or services using Docker containers.

---

This lab setup is ideal for developers, IT professionals, or hobbyists looking for a flexible, private, and powerful lab environment for experimentation and learning.
