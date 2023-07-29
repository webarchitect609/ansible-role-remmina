Ansible Role: Remmina
=======================

[![Build Status](https://github.com/webarchitect609/ansible-role-remmina/workflows/build/badge.svg?branch=master)](https://github.com/webarchitect609/ansible-role-remmina/actions?query=workflow%3Abuild)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-remmina?sort=semver)](https://github.com/webarchitect609/ansible-role-remmina/releases)
[//]: # (TODO Replace '00000' with the role id, which can be found by `ansible-galaxy role info webarchitect609.remmina | grep -oP "\bid:\s?\d+"`)
[![Downloads](https://img.shields.io/ansible/role/d/00000)](https://galaxy.ansible.com/webarchitect609/remmina)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-remmina)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/webarchitect609)

Installs [Remmina](https://remmina.org/) from the official repository.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.remmina }

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
