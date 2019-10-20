Role Name
=========

install_k8s/join-workers

Finishes to setup the cluster's topology by adding the worker nodes to it.

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
  - install_k8s/create-cluster


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: join-workers }

License
-------

BSD


