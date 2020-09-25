# Ansible Role: umask

An Ansible Role that updates the system umask.

[![Actions Status](https://github.com/tristan-weil/ansible-role-umask/workflows/molecule/badge.svg?branch=master)](https://github.com/tristan-weil/ansible-role-umask/actions)

## Role Variables

Available variables are listed below, (see also `defaults/main.yml`).

Mandatory variables:

| Variable      | Description |
| :------------ | :---------- |

Optional variables:

| Variable      | Default | Description |
| :------------ | :------ | :---------- |
| umask_mode    | "027"   | the umask to apply |

## Example Playbook

    - hosts: 'webservers'
      roles:
        - role: 'ansible-role-umask'

## Todo

None.

## Dependencies

None.

## Supported platforms

See [meta/main.yml](https://github.com/tristan-weil/ansible-role-umask/blob/master/meta/main.yml)

## License

See [LICENSE.md](https://github.com/tristan-weil/ansible-role-umask/blob/master/LICENSE.md)
