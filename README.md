# Ansible role: etcresolvconf

An ansible role for managing /etc/resolv.conf

## Requirements

A GNU/Linux machine.

## Role Variables

Defaults for role:
```
etcresolvconf_dnsservers:
  - 9.9.9.9
  - 149.112.112.112

etcresolvconf_domain: Null
etcresolvconf_search: []
```

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sgaduuw.etcresolvconf, etcresolvconf_dnsservers: ['1.1.1.1', '8.8.8.8', '9.9.9.9'] }

## License

MIT

## Author Information

Created by Eelco Wesemann (Sgaduuw), 2020
