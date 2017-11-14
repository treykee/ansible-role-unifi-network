Ansible Role: UniFi Controller
=========

Installs Ubiquiti UniFi Controller software from source on RHEL/CentOS

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

unifi_controller_version: 5.6.22

Set the version of the UniFi controller to be installed.

unifi_controller_java_version: 1.8.0

Set the version of Java required to support the version of the UniFi Controller specificed. This should only be changed when the default version of Java specified in the role defaults no longer meets the package requirements.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: treykee.unifi-controller }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)