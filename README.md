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

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

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
