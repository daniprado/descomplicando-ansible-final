Role Name
=========

install_k8s/install-k8s

Installs the required software in the given machines.

Requirements
------------

N/A

Role Variables
--------------

N/A

Dependencies
------------

Roles required from the same project:

  - provisioning/create


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: install-k8s }

License
-------

BSD


