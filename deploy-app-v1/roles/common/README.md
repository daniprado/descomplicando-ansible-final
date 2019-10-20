Role Name
=========

deploy-app-v1/common

Deploys first version of the App.

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
         - { role: common }

License
-------

BSD

