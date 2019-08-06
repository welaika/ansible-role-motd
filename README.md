Ansible Role Motd
=================

[![Build Status](https://travis-ci.org/welaika/ansible-role-motd.svg?branch=master)](https://travis-ci.org/welaika/ansible-role-motd)

This role install a motd on the server.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None :)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
     - role: ansible-role-motd
```

License
-------

MIT

Testing
-------

Install molecule

`$ pip3 install --user 'molecule[docker]'`

Start docker and run

`$ molecule test`

Author Information
------------------

made with ❤️ and ☕️ by [weLaika](https://dev.welaika.com)
