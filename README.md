**INTRODUCTION**
===============

This a project to set a local server and deploy (micro) services in it.

This project is thinking to be applied on a Debian base OS, at least, the needed setup. Microservices will run on any environment with Docker ^^.

## Requirements

We need Ansible and Python for it:

```bash
$ sudo apt install ansible python3
#$ sudo ln -s /usr/bin/python3 /usr/bin/python
```

## Ansible

Execute the following playbook to set the server:

```bash
$ ansible-playbook -i inventory --ask-become-pass playbooks/setup.yaml
```
