# Ansible Role: Ntp [![Build Status](https://travis-ci.org/manala/ansible-role-ntp.svg?branch=master)](https://travis-ci.org/manala/ansible-role-ntp)

:exclamation: [Report issues](https://github.com/manala/ansible-roles/issues) and [send Pull Requests](https://github.com/manala/ansible-roles/pulls) in the [main Ansible Role repository](https://github.com/manala/ansible-roles) :exclamation:

This role will deal with the setup of [Ntp](http://www.ntp.org/).

It's part of the [Manala Ansible stack](http://www.manala.io) but can be used as a stand alone component.

## Requirements

None.

## Dependencies

None.

## Installation

### Ansible 2+

Using ansible galaxy cli:

```bash
ansible-galaxy install manala.ntp
```

Using ansible galaxy requirements file:

```yaml
- src: manala.ntp
```

## Role Variables

### Definition

| Name                                  | Default | Type  | Description                            |
| ------------------------------------- | ------- | ----- | -------------------------------------- |
| `manala_ntp_install_packages`         | ~       | Array | Dependency packages to install         |
| `manala_ntp_install_packages_default` | ['ntp'] | Array | Default dependency packages to install |

## Example playbook

```yaml
- hosts: servers
  roles:
    - { role: manala.ntp }
```

# Licence

MIT

# Author information

Manala [**(http://www.manala.io/)**](http://www.manala.io)
