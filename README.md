# Ansible Role: UniFi Network

Installs Ubiquiti UniFi Network application on RHEL and Debian based distributions.

## Requirements

None.

## Role Variables

Available variables are listed below. For default values see `defaults/main.yml`:

```yaml
unifi_version: ""
```

Set the version of the UniFi Network application to be installed.

```yaml
unifi_java_version: ""
```

Set the version of Java required to support the version of the UniFi Network application specificed.
**Note**: This should only be changed when the version of Java specified in the role defaults no longer meets the package requirements.

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - treykee.unifi_network
```

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)
