AnsibleRoleOsLinuxInstallAptitude
=========

Ansible from version 2.4 is using by default Aptitude as a default package manager in case of Debian based operating systems. This Ansible role will install aptitude on Debian based operating systems.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Below ther's example playbook which can be used:

    - hosts: servers
      roles:
         - { role: kamikazestar.AnsibleRoleOsLinuxInstallAptitude }

License
-------

MIT

Author Information
------------------

[Marcin Slabonski](https://github.com/kamikazestar)
