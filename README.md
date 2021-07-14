andrewrothstein.galaxify
===========================
![Build Status](https://github.com/andrewrothstein/ansible-galaxify/actions/workflows/build.yml/badge.svg)

A script I use for branding/licensing/CI/CD testing of Ansible roles form the get-go.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.galaxify
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
