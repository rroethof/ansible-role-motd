# Message of the Day

[![Build Status](https://travis-ci.org/rroethof/ansible-role-motd.svg?branch=master)](https://travis-ci.org/rroethof/ansible-role-motd)

`motd` is an ansible role which will:

 * coping of motd files
 * removing of motd files
 * updating the motd

## Requirements

This role requires Ansible 1.6 or higher.

## Role Variables

motd_template: $nameoftemplatefile

## Examples

```yaml
    - hosts: servers
      roles:
         - motd
```

## License

This role was created in 2015 by Ronny Roethof
