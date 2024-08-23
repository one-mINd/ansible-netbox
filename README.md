Docker Netbox
=========

A simple role to setup [linuxserver/netbox](https://docs.linuxserver.io/images/docker-netbox/) project with Redis and PostgresDB inside docker containers. 

Role Variables
--------------

You can check defaults/main file to see possible variables. To learn more about variables see linuxserver documentation [here](https://docs.linuxserver.io/images/docker-netbox/#environment-variables-e).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---
- name: Configure netbox on target hosts
  hosts: all
  remote_user: root
  become: yes
  roles:
    - ansible-netbox
```

License
-------

BSD
