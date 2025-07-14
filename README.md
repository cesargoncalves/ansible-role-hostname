Ansible role hostname
=========

An Ansible role that configures the system hostname consistently across supported Linux distributions and reboots the host if required.

Requirements
------------

None

Role Variables
--------------

- `hostname_fqdn`: name of the host, by default uses inventory_hostname

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  become: true
  roles:
     - cesargoncalves.hostname
```

License
-------

GPL-3.0

Author Information
------------------

Role created by [cesargoncalves](https://github.com/cesargoncalves)
