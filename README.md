Authorized Keys
===============
[![Galaxy](https://img.shields.io/badge/galaxy-samdoran.authorized_keys-blue.svg?style=flat)](https://galaxy.ansible.com/samdoran/authorized_keys)

Manage ssh `authorized_keys`.

Requirements
------------

None

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `authorized_keys` | `[]` | List of keys to be added or removed. See `defaults/main.yml` for examples. |


Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - samdoran.authorized_keys

License
-------

Apache 2.0
