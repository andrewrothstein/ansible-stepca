andrewrothstein.stepca
=========

![Build Status](https://github.com/andrewrothstein/ansible-stepca/actions/workflows/build.yml/badge.svg)

Installs the [Step CA](https://github.com/smallstep/certificates).

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
    - andrewrothstein.stepca
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
