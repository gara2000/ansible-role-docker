Docker Role
=========

This role installs and configures docker on the target server

Requirements
------------

- Runs on: Ubuntu 22.04

Role Variables
--------------

Dependencies
------------

No dependencies

Example Playbook
----------------

```bash
- hosts: servers
  become: yes
  roles:
      - gara2000.docker
```

License
-------

BSD
