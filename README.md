Role Name
=========

Role to install hashicorp vault binary into:
  /opt/soft/auth/hashicorp/vault/<version>

Requirements
------------

Target needs unzip, and probably curl / wget or similar...

Role Variables
--------------

see defaults/main.yml
  e.g., vault_version: 1.15.0

Dependencies
------------

community.general: ">=1.3.0"

Example Playbook
----------------

see: https://github.com/joe-opensrc/ansible-harness-hashicorp-vault
  although, it's not very illuminating :) 

License
-------

GPL-v2-only

Author Information
------------------

Joe OpenSrc
