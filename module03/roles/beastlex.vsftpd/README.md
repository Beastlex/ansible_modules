Role Name
=========

Task 02 module 03. Role for install Apache web server to nodes in lab

Requirements
------------

Target platform OS is CentOS 8

Role Variables
--------------

Defaults:
* dir_for_anonymous - root dir for anonymous access
* subdisrs__for__upload - sub directories for upload file
* anon_mkdir - enable mkdir for anonymous (NO by default)

Vars:
**** ports_for_open - ports for open in firewall (20 and 21 by default)

Dependencies
------------

No Dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Aleksandr Zverev, EPAM student
