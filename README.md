Role and Dockerfile for ophidia-terminal application
=======================================================

Roles and Dockerfiles to install the ophidia-terminal application:

* To be updated

Introduction
------------

The repository contains ansible-roles that are published in
ansible galaxy: https://galaxy.ansible.com/indigo-dc/ophidia-terminal/

The directory docker-ophidia-terminal is linked to
dockerhub with automatic build. This image can run
ophidia-terminal client application for the Ophidia Big Data framework

Requirements
------------

No aditional requirements

Role Variables
--------------

The variables that can be passed to this role and a brief description
about them are as follows.



Dependencies
------------

None for now

Install the Playbook
--------------------

To install the role:

```
$ ansible-galaxy install indigo-dc.ophidia-terminal
```

Run the playbook
----------------

An example of playbook for the ophidia-terminal:

```
---
- hosts: localhost
  remote_user: root
  roles:
    - indigo-dc.ophidia-terminal
```

Or execute:

```
$ ansible-playbook /etc/ansible/roles/indigo-dc.ophidia-terminal/tests/ophidia-terminal.yml
```

Run the ophidia-terminal application
------------------------------------

To be updated

License
-------

Apache v2

Author Information
------------------

Mario David: mariojmdavid@gmail.com
LIP and Indigo-DataCloud project

Acknowledgments
---------------

* Ophidia and CMCC

