[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/aws_bootstrap/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/aws_bootstrap/tree/main)

Role Description
=========

Installs boto3 for CentOS Stream 9.

Requirements
------------

EPEL and pip installed before running this role.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - robertdebock.epel
    - geerlingguy.pip
    - aws_s3_bootstrap
```

License
-------

BSD
