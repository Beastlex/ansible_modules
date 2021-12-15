Role Name
=========

Task 01 module 03.
Role for install Apache web server to nodes in lab 

Requirements
------------

Target platfors OS is CentOS 8

Role Variables
--------------

* ports_for_open - list of open ports for firewall rules
* default_file - file for index.html in root dir of nginx 

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
