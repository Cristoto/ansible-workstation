# Ansible WorkStation

This repository contains [Ansible](http://docs.ansible.com/) instructions for setting up my machine over Ubuntu.

## Requirements

To use this repository you must [install ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) version 2.8 or higher, and snap on your system.

To install snap on your system use the following command.

```bash
sudo apt update -y && sudo apt install -y snapd
```

## Quick Start

Set execution permission to setup.sh file.

```bash
chmod +x setup.sh
```

Run the setup script.

```bash
./setup.sh
```
If at the end of the script the applications do not appear in the applications menu, restart the PC.

### Roles repositories

The following list shows all the roles used in the playbook.

- [Oh my Zsh](https://github.com/gantsign/ansible-role-oh-my-zsh)
- [Nodejs](https://github.com/geerlingguy/ansible-role-nodejs)
- [Yarn](https://github.com/Oefenweb/ansible-yarn)
- [Docker](https://github.com/geerlingguy/ansible-role-docker)
- [Virtualbox](https://github.com/Oefenweb/ansible-virtualbox)