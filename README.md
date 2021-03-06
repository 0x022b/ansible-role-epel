# Ansible Role: EPEL

![Ansible Galaxy](https://github.com/0x022b/ansible-role-epel/workflows/Ansible%20Galaxy/badge.svg)

Ansible role that configures [Extra Packages for Enterprise Linux][epel] repository.

## Requirements

None.

## Role Variables

Available variables are listed below with default values.

```yaml
epel_package_state: present
```

Controls the state of the repository package.

## Dependencies

None.

## Example Playbook

```yaml
- hosts: servers
  roles:
    - role: 0x022b.epel
```

## Versioning

This project uses [Semantic Versioning][semver].

## License

MIT

[epel]: https://fedoraproject.org/wiki/EPEL
[semver]: https://semver.org/
