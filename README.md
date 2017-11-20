Ansible Role: UniFi Controller
=========

[![Build Status](https://travis-ci.org/treykee/ansible-role-unifi-controller.svg?branch=master)](https://travis-ci.org/treykee/ansible-role-unifi-controller)

Installs Ubiquiti UniFi Controller software from source on RHEL/CentOS

Requirements
------------

None.

Role Variables
--------------

unifi_controller_version: 5.6.22

Set the version of the UniFi controller to be installed.

unifi_controller_java_version: 1.8.0

Set the version of Java required to support the version of the UniFi Controller specificed.
**Note**: This should only be changed when the version of Java specified in the role defaults no longer meets the package requirements.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: treykee.ansible-role-unifi-controller }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)