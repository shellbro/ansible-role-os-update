os-update
=========

Ansible role for updating OS (RedHat, Debian).

It uses `package` module to abstract away discrepancy between `yum` and `dnf` package managers in RedHat-based distributions and ordinary `apt` module in distributions based on Debian.

Requirements
------------

Ansible version >= 2.0.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      serial: 1
      roles:
        - shellbro.os-update

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
