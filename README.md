yggdrasil
=========

Deploy yggdrasil using Ansible.

Dependencies
------------

ansible_lsb needs additional packages on some systems,
those need to be available


Role Variables
--------------

For available variables take a look at the config template,
it is currently the only place with variables.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: yggdrasil
           become: yes

License
-------

AGPLv3

Author Information
------------------

Jan Christian Grünhage <jan.christian@gruenhage.xyz>
