# Ansible Role: UniFi Network

Installs Ubiquiti UniFi Network application on RHEL and Debian based distributions.

## Requirements

None.

## Role Variables

Available variables are listed below. For default values see `defaults/main.yml`:

```yaml
unifi_version: ""
```

## Dependencies

None

## Example Playbook

```yaml
- hosts: servers
  roles:
    - treykee.unifi_network_application
```

## License

MIT / BSD

## Author Information

This role was created in 2017 by [Trey Keenon] (<https://www.treykee.me/>)
