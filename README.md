# Ansible Role: ntp

This role will deal with the setup of __ntp__.

It's part of the Manala <a href="http://www.manala.io" target="_blank">Ansible stack</a> but can be used as a stand alone component.

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
