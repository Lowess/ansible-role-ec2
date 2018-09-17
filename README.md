ansible-role-ec2
================

Ansible role used to provision ec2 instances

Requirements
------------

* `boto` and `boto3` must be installed on the controller

Role Variables
--------------

TODO

Dependencies
------------

None

Example Playbook
----------------

```yaml
- name: Provision an EC2 instance
  hosts: localhost
  connection: local
  roles:
     - role: Lowess.ec2
```

License
-------

BSD

Author Information
------------------

This role was created in 2018 by Florian Dambrine, used in [AWS-360](https://slides.com/floriandambrine/aws360/) course.

