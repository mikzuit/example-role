Role Name
=========

example-role

Requirements
------------

molecule >=3.3.4
  docker driver
ansible >=2.11.11

Role Variables
--------------

This is sample role molecule tested and linted, I kind of like using latest version
of literally everything this brought me to share this role as a sample for you people won't find any working role tested for latest OS. Also using a self created ubuntu:21.04 docker image on dockerhub.

default/vars
web_content variable contains index.html file content

vars
Debian specific and Rhel8 specific

Dependencies
------------

non dependant roles

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Mik Zuit
https://github.com/mikzuit