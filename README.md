vnc-server
==========

[![Build Status](https://travis-ci.org/shellbro/ansible-role-vnc-server.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-vnc-server)

Ansible role that sets up a VNC server on CentOS 7.

Requirements
------------

Ansible version >= 2.3.

Role Variables
--------------

- user - user name used to start a VNC server
- display - display number (by default :2)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
      - role: shellbro.vnc-server
        user: shellbro
        display: :5

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
