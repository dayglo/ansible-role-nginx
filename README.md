Ansible Role: Nginx
=========

Install Nginx on CentOS servers.

Note: this role won't change nginx configurations.

Requirements
------------

Written in Ansible 1.9.*

Role Variables
--------------

None.

Dependencies
------------

Requires epel or some other yum repository with nginx package.

Example Playbook
----------------

    - hosts: servers
      roles:
        - nginx

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2016 by [Juwai Limited](http://www.juwai.com).
