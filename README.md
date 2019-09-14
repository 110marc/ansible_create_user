ansible_create_user
=========

Role is intended to create a user on a Linux system, set its password and force it to be changed on the first login.

Requirements
------------

_Optional:_ Run it with sudo password prompt:
```
ansible-playbook --ask-become-pass main.yml -l remote
BECOME password: 
```

Role Variables
--------------

Variables present are username and password.

Dependencies
------------

No dependencies.

Example Playbook
----------------

An example of how to use your role:

    - hosts: servers
      become: yes
      roles:
         - ansible_create_user

License
-------

BSD

Author Information
------------------

> https://github.com/110marc
