==================
ansible-role-boto3
==================

Ansible role to install AWS's boto3 library

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-boto3.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-boto3
* Bugs: https://bugs.launchpad.net/ansible-role-boto3

Description
-----------

AWS's boto3 is a simple client library for operating AWS.

Requirements
------------

See `bindep.txt` for role dependencies.

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install AWS's Boto3 lib 
      hosts: nodepool
      roles:
        - ansible-role-boto3
