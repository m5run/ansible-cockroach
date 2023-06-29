[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

cockroach
==========


Installs cockroach

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------
- cockroach_user: cockroach
- cockroach_group: cockroach
- cockroach_version: "v23.1.4"
- cockroach_join_addrs: The list of addresses to join in the cluster
- cockroach_systemd_template: "cockroach.service.j2"
- cockroach_sysconf_template: "sysconf.j2"

Dependencies
------------

None

Example Playbook
----------------

Install cockroach
```yaml
- hosts: all
  roles:
    - m5run.cockroach
```

License
-------

BSD

Author Information
------------------

Todd Davis
