# Ansible Jupyter [![Build Status](https://travis-ci.org/fede2cr/ansible_jupyter.svg?branch=master)](https://travis-ci.org/fede2cr/ansible_jupyter)


Recipes for installing Jupyter notebook with extra stuff.

## Description

Ansible recipes for installing Jupyter notebook via python pip. This works on Debian/Ubuntu or Arch distributions.

## Usage

Install the latest version of Ansible on a management computer, python2 on the computers you want to install Jupyter notebook, and then run:

```bash
ansible-playbook install-jupyter.yml -i inventory/hosts -K
```

It also does:

- [x] Installs the bash kernel
- [x] Configures default user with password "greencore"
