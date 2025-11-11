Ansible SNMP Deamon role
=========

Install and configure snmpd for librenms.

Role Variables
--------------

Available variables are listed below, along with default values in `vars/main.yaml`

```
snmp_community: public
snmp_location: City
snmp_email: mail@example.com
```

Dependencies
--------------

None

Example Playbook
--------------

```
- hosts: localhost
  roles:
    - myckakamil.snmpd
```

Author Information
--------------

This role was created in 2025 by [Kamil Myćka](https://github.com/myckakamil)
