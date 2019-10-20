Role Name
=========

provisioning/create

Creates the expected VM instances in AWS.

Requirements
------------

Packages:
  - boto* (EC2 dependency)

Role Variables
--------------

Not exhaustive list:

  - app_env: name given to the group of VMs to be created. Mandatory.
  - instance_type: capabilities (type) of the VMs to be created.
  - image: OS image to be installed in the VMs.
  - count: number of VMs to be created.

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: create, environment: 'dev' }

License
-------

BSD

