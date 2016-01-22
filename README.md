# Ansible Role: PA11y

[![Build Status](https://travis-ci.org/nerdstein/ansible-role-pa11y.svg?branch=master)](https://travis-ci.org/nerdstein/ansible-role-pa11y)

Installs PA11y, an accessibility scanning tool, on any Linux or UNIX system.

## Requirements

`npm` should be installed and working.

## Role Variables

None

## Dependencies

- geerlingguy.node

## Example Playbook

    - hosts: servers
      roles:
        - nerdstein.pa11y

After the playbook runs, `pa11y` will be accessible via normal system accounts.

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Adam Bergstein](http://nerdstein.net/).
