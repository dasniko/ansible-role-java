# Ansible Role for Java SDK

[Ansible](https://www.ansible.com/) role for Java SDK (OpenJDK) on an Ubuntu environment.

## Role Variables

- `java_version` (string) The version of the JDK to install.

## Dependencies

_none_

## Example Playbook

    - hosts: your_servers
      roles:
        - role: dasniko.java
          java_version: 8

## License

MIT
