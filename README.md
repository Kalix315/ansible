# Ansible Automation Project

This repository contains a collection of Ansible playbooks for managing various systems and performing different tasks.

# Table of Contents

- [Ansible Automation Project](#ansible-automation-project)
  - [Project Structure](#project-structure)
  - [Usage](#usage)
  - [Ansible Automation Platform Project Setup](#ansible-automation-platform-project-setup)
    - [Prerequisites](#prerequisites)
      - [Ansible Automation Platform installed]( ansible-automation-platform-installed).
    - [Steps](#steps)
      - [1. Clone the Repository](#1-clone-the-repository)
      - [2. Create a Project](#2-create-a-project)
      - [3. Create a Job Template](#3-create-a-job-template)

## Ansible Automation Project

This repository contains a collection of Ansible playbooks for managing various systems and performing different tasks.

### Project Structure

- [**cisco_project**](cisco_project):
  - [backup_running_config.yaml](cisco_project/backup_running_config.yaml): Backup Cisco running configuration.
  - [configure_banner.yaml](cisco_project/configure_banner.yaml): Configure banner on Cisco devices.
  - [configure_loopback.yaml](cisco_project/configure_loopback.yaml): Configure loopback interface on Cisco devices.
  - [show_run.yaml](cisco_project/show_run.yaml): Display running configuration on Cisco devices.

- [**linux_project**](linux_project):
  - [install_package.yaml](linux_project/install_package.yaml): Install a package on Linux.
  - [linux_command.yaml](linux_project/linux_command.yaml): Execute a Linux command.
  - [read_content_file.yaml](linux_project/read_content_file.yaml): Read content from a file on Linux.
  - [uninstall_package.yaml](linux_project/uninstall_package.yaml): Uninstall a package on Linux.
  - [upgrade_system.yaml](linux_project/upgrade_system.yaml): Upgrade the Linux system.

- [**poc_project**](poc_project):
  - [read_json_and_take_action.yaml](poc_project/read_json_and_take_action.yaml): Read JSON file and take actions.

- [**vmware_project**](vmware_project):
  - [gather_info.yaml](vmware_project/gather_info.yaml): Gather information from VMware infrastructure.

- [**windows_project**](windows_project):
  - [install_chrome.yaml](windows_project/install_chrome.yaml): Install Google Chrome on Windows.
  - [install_package.yaml](windows_project/install_package.yaml): Install a package on Windows.
  - [install_updates.yaml](windows_project/install_updates.yaml): Install system updates on Windows.
  - [list_updates.yaml](windows_project/list_updates.yaml): List available updates on Windows.
  - [uninstall_chrome.yaml](windows_project/uninstall_chrome.yaml): Uninstall Google Chrome on Windows.
  - [uninstall_package.yaml](windows_project/uninstall_package.yaml): Uninstall a package on Windows.
  - [uninstall_updates.yaml](windows_project/uninstall_updates.yaml): Uninstall system updates on Windows.
  - [verifica_chrome.yaml](windows_project/verifica_chrome.yaml): Verify the installation of Google Chrome on Windows.

- [**windows_playbook.yaml**](windows_playbook.yaml): An overarching playbook for Windows tasks.

### Usage

Include instructions or examples on how to use the playbooks in your project.

### Ansible Automation Platform Project Setup

This section provides instructions on setting up an Ansible project on Ansible Automation Platform using playbooks from this GitHub repository.

#### Prerequisites

- Ansible Automation Platform installed. Follow the official installation guide: [Ansible Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

### Steps

#### 1. Clone the Repository

Clone this Ansible playbooks repository to your local machine.

```bash
git clone https://github.com/Kalix315/ansible.git
```

#### 2. Create a Project

1. In the Ansible Automation Platform, navigate to the Projects section.
2. Click on "Create Project" and provide a name and description for your project.
3. Choose the integration type as "GitHub".
4. Enter your GitHub repository URL and select the branch you want to use.
5. Configure other settings such as inventory and credentials as needed for your project.
6. Save the project configuration.
7. Your Ansible Automation Platform is now connected to your GitHub repository, and you've created a project ready for automation.

Feel free to customize these steps based on your specific requirements and environment.

#### 3. Create a Job Template

Now that you have set up your Ansible Automation Platform project and connected it to your GitHub repository, follow these steps to create a job template:

1. In the Ansible Automation Platform, navigate to the Job Templates section.

2. Click on "Create Job Template" and provide a name and description for your job template.

3. Choose the project you created earlier from the "Project" dropdown menu.

4. Select the playbook you want to use from the "Playbook" dropdown menu. For example, you can choose a playbook from the `cisco_project`, `linux_project`, `poc_project`, `vmware_project`, or `windows_project` directories.

5. Configure other settings such as inventory, credentials, and job options as needed for your specific playbook.

6. Save the job template.

7. Your job template is now ready for execution. You can run it manually, schedule it, or integrate it into other automation workflows.

Repeat these steps for each playbook you want to create a job template for.

Feel free to customize these steps based on your specific requirements and environment.
