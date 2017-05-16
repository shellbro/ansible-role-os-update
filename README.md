Role Name
=========

Ansible role for updating OS.

It uses `package` module to abstract away discrepancy between `yum` and `dnf` in RedHat-based distributions and ordinary `apt` module in distributions based on Debian.

Requirements
------------

Ansible version >= 2.0.0.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - name: apply updates
      hosts: all
      serial: 1
      roles:
         - shellbro.os-update

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
