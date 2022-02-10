# Ansible Role: UniFi Network Application

Installs Ubiquiti UniFi Network Application software on RHEL/CentOS Debian/Ubuntu.

## Requirements

None.

## Role Variables

Available variables are listed below. For default values see `defaults/main.yml`:

```yaml
unifi_na_version: ""
```

Set the version of the UniFi Network Application to be installed.

```yaml
unifi_na_java_version: ""
```

Set the version of Java required to support the version of the UniFi Network Application specificed.
**Note**: This should only be changed when the version of Java specified in the role defaults no longer meets the package requirements.

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - treykee.ansible-role-unifi-network_application
```

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)
