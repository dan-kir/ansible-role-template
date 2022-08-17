ansible-role-template
==============================
[![Actively Maintained](https://img.shields.io/badge/Maintenance%20Level-Actively%20Maintained-green.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)


Requirements
------------
Requires Ansible 2.10 or later.


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------

    - hosts: all
      become: yes
      become_method: sudo
      roles:
        - ansible-debian-11-blah


Example Inventory
-----------------

*inventory.ini*

    [servers]
    192.168.0.11 ansible_ssh_user=admin

*inventory.yml*

    ---
    all:
      hosts:
        192.168.0.11:
      vars:
        ansible_ssh_user: admin

License
-------
GPL-3.0 License


Author Information
------------------
This role was created by Dan Kir
