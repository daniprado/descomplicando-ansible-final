Role Name
=========

deploy-app-v2/common

Deploys second version of the App.

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
  - deploy-app-v1/common


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: common }

License
-------

BSD

