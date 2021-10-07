# Ansible Role: UniFi Controller

[![Build Status](https://travis-ci.org/treykee/ansible-role-unifi-controller.svg?branch=master)](https://travis-ci.org/treykee/ansible-role-unifi-controller)

Installs Ubiquiti UniFi Controller software on RHEL/CentOS Debian/Ubuntu.

## Requirements

None.

## Role Variables

Available variables are listed below. For default values see `defaults/main.yml`:

```yaml
unifi_controller_version: ""
```

Set the version of the UniFi controller to be installed.

```yaml
unifi_controller_java_version: ""
```

Set the version of Java required to support the version of the UniFi Controller specificed.
**Note**: This should only be changed when the version of Java specified in the role defaults no longer meets the package requirements.

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - treykee.ansible-role-unifi-controller
```

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)
