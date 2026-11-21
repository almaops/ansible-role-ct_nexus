# DEPRECATION NOTICE
This role has been deprecated in favor of [almaops.common.ct_nexus](https://github.com/almaops/ansible-collection-common/tree/master/roles/ct_nexus)

almaops.ct_nexus
==========

This ansible role installs a docker container with Nexus OSS

Requirements
------------

Docker running on target host

Role Variables
--------------

Look into [./defaults/main.yml](./defaults/main.yml)

Example Playbook
----------------

```
- hosts: servers
  roles:
    - role: almaops.ct_nexus
      ct_nexus_bind_addr: '192.168.0.2'
```

License
-------

[MIT License](./LICENSE)


Author Information
------------------
Valentin Gostev, <val@le.lc>
Dmitrii Kashin, <freehck@freehck.com>
