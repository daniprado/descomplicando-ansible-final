Role Name
=========

install_k8s/install-helm

Installs helm in the master node of the cluster being created.

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
         - { role: install-helm }

License
-------

BSD


