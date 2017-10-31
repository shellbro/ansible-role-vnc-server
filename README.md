vnc-server
==========

Ansible role that sets up VNC server on CentOS 7.

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
      - name: shellbro.vnc-server
        user: shellbro
        display: :5

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
