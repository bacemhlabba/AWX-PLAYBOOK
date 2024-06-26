# AWX Playbook Repository

Welcome to the AWX Playbook Repository! Here, you'll find a collection of Ansible playbooks tailored to configuring and managing AWX, the open-source version of Ansible Tower.

## Contents

Explore our playbook arsenal:

- `playbook.yml`: The primary playbook for configuring AWX.
- `run_command.yml`: Execute commands on remote hosts.
- `run_shell_command.yml`: Run shell commands on remote hosts.
- `shutdown.yml`: Shut down remote hosts gracefully.

## Usage

Get started with these simple steps:
Alternatively, use the AWX web interface: These playbooks can also be executed through the AWX web interface. Import the playbooks into AWX, configure job templates, and launch them with ease through the UI.
1. **Clone this repository** to your local machine:

   ```bash
   git clone https://github.com/bacemhlabba/AWX-PLAYBOOK.git
1- Modify the inventory.ini file to match your environment. Ensure SSH access to listed hosts.
2- Update variables in group_vars/ and host_vars/ directories to fit your needs.
3- Run a playbook using the command:
   ```bash
   ansible-playbook -i inventory.ini playbook.yml
Replace playbook.yml with the playbook you wish to execute.

Requirements
Ensure the following prerequisites are met:

Ansible is installed on the machine where you'll run the playbook.
SSH access to AWX server and target hosts is established.
inventory.ini is properly configured with necessary host information.
Contributing
Your contributions are valuable! Feel free to submit pull requests or open issues for improvements.

License
This project is licensed under the MIT License. Happy automating! 🤖✨
