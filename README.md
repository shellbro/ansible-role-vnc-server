shellbro.vnc_server
===================

[![Build Status](https://travis-ci.org/shellbro/ansible-role-vnc-server.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-vnc-server)

https://galaxy.ansible.com/shellbro/vnc_server

Ansible role for setting up a VNC server on CentOS 7

Requirements
------------

Ansible version >= 2.4

Role Variables
--------------

* user - user to start a VNC server (required)
* password - default VNC password (by default `password`)
* display - display number (by default `:2`)

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: shellbro.vnc_server
          user: shellbro
          password: vncpassword
          display: :3

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
