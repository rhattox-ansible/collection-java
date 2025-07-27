# collection-java

Ansible Collection for Java Installation

## Installation

You can install this collection using Ansible Galaxy:

```bash
ansible-galaxy collection install rhattox-ansible.colletion-java
```

## Usage

To use this collection in your playbook, include the role as follows:

```yaml
- hosts: all
  roles:
    - role: rhattox-ansible.colletion-java.java
```

## Requirements

- Ansible 2.9+
- Supported on Linux

## Description

This collection provides an Ansible role to automate the installation and configuration of Java on your systems.
