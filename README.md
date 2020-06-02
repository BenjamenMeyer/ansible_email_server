email_server
=========

Postfix+Dovecot email server; PostgresSQL Server used if needed.

Requirements
------------

* n/a

Role Variables
--------------

* users

Dependencies
------------

* base_system

Example Playbook
----------------

    - hosts: servers
      roles:
         - email_server

License
-------

Apache

Author Information
------------------

Ben Meyer
