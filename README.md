Docker
=========

[![Build Status](https://travis-ci.com/charliemaiors/docker.svg?token=yh45AABQopkgvYGSpm7Z&branch=master)](https://travis-ci.org/charliemaiors/docker)

This role installs docker-ce on the host machine.

Requirements
------------

The only requirement is the presence of python on the target machine.

Role Variables
--------------

This role use only ```docker_start``` boolean variable for systemd enabled services (the default is ```true```).

Dependencies
------------

No dependencies

Example Playbook
----------------

The role could be used as normal role:

    - hosts: servers
      roles:
         - { role: docker }

License
-------

BSD
