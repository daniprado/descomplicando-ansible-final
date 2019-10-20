Role Name
=========

install_k8s/create-cluster

Creates the K8s cluster by setting up the master node.

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
  - install_k8s/install-k8s


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: create-cluster }

License
-------

BSD

