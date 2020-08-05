Ansible Role: Lynis
=========

An Ansible Role that installs Lynis on CentOS or Ubuntu using [CISOfy Software Repository (Community)](https://packages.cisofy.com/community/)

Requirements
------------

* python-apt (python 2)
* python3-apt (python 3)

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
---
- hosts: "{{ target_host }}"
  become_method: sudo
  roles:
    - ansible-role-lynis
```

License
-------

MIT

Author Information
------------------

Rafael Coutinho
