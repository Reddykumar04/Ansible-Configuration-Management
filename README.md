# README.md
# Automatic Configuration Management Across Environments with Ansible

## Overview
This project automates configuration management across multiple environments using Ansible. It ensures consistency, scalability, and efficiency in infrastructure deployment.

## Setup Instruction
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Install Ansible:
   ```bash
   sudo apt update && sudo apt install ansible -y
   ```
3. Install required Ansible roles and collections:
   ```bash
   ansible-galaxy install -r requirements.yml
   ```
4. Run the Ansible playbook:
   ```bash
   ansible-playbook -i inventory.ini server_setup.yml
   ```

## Features
- Environment-based configuration management
- Modular roles for flexibility
- Automated deployment with GitHub Actions
- Predefined role dependencies for enhanced functionality
- Jinja2 templating for custom Nginx configurations
- Static website deployment with Ansible
- Custom variables for flexible configurations

## License
This project is licensed under the MIT License.
