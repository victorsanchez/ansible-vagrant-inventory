#!/usr/bin/env python
# -*- coding: utf-8 -*-

'''
##### This is a dynamic invetory script that converts .vagrant/provisioners/ansible/inventory to a json format. It is now based on original ansible inventory code. Here's ans example file structure:

##### ├── Vagrantfile
##### ├── ansible.cfg
##### ├── manualrun.yml
##### ├── group_vars
##### │   └── all.yml
##### ├── inventory
##### ├───├── my_inventory.yml
##### │   └── vagrant_inventory
##### │       ├── README.md
##### │       └── vagrant.py
##### ├── vagrant.yml

##### You can find a [vagrant](https://github.com/gitinsky/ansible-role-vagrant) that sets up your local user in vagrant vms usefull for eccessing them.

#### Requirements
#####jinja2
##### pyyaml
```pip install jinja2 pyyaml```

'''

print '{}'
