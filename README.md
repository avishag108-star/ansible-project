# AWS & Ansible DevOps Project 🚀

This project automates the deployment of Docker containers on AWS using Ansible.

## Features
* **Dynamic Inventory:** Automatically finds servers on AWS using Tags.
* **Docker Support:** Deploys Nginx and MySQL inside containers.
* **Smart Conflict Resolution:** Automatically stops old services to free up ports.

## How to Run
1. Update `ansible.cfg` with your key path.
2. Run the playbook:
   ansible-playbook site.yml