# Ansible Automation Project

This repository contains a collection of Ansible playbooks for managing various systems and performing different tasks.

## Project Structure

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

## Usage

Include instructions or examples on how to use the playbooks in your project.

## Contributing

If you'd like to contribute to this project, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [License Name] - see the [LICENSE.md](LICENSE.md) file for details.
