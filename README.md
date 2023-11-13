# Ansible Playbook for Gneiss
This is an Ansible playbook intended for use with a Gneiss installation.

## Usage
```sh
ansible-playbook --ask-become-pass --extra-vars hostname=<HOSTNAME> [--tags [nvidia]] main.yaml
```
