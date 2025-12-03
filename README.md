Role Name
=========

Ansible Role that install and configure Vector on CentOS

Requirements
------------

Target OS: CentOS 8, CentOS 9

Ansible version >= 2.10

Role Variables
--------------

Variable | Description | Example
-------- | -------- | -------
vector_version | Vector vesion | "0.51.1"
vector_path | Installation directory | "/opt/vector"

Dependencies
------------

--

Example Playbook
----------------
``` 
- hosts: servers
  roles:
    - vector
```
License
-------

MIT

