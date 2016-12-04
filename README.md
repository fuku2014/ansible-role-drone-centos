drone
=========

This role installs drone.

Requirements
------------

centos

Role Variables
--------------

* drone_database_driver: drone database driver
* drone_database_config: drone database config
* drone_remote_driver: drone remote driver
* drone_remote_config: drone remote config
* drone_port: drone port

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: servers
      roles:
         - fuku2014.drone

License
-------

Apache2.o

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
