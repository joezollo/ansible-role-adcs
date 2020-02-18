Ansible Role: Active Directory Certificate Services
=========

(WORK IN PROGRESS - DO NOT USE)

Installs or removes Active Directory Certificate Services on a Windows Server.

Requirements
------------
* Windows Server 2012
* Windows Server 2012 R2
* Windows Server 2016
* Windows Server 2019

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    adcs_state: present

The state of this role, present (default) will install the latest version, absent will remove it.

  adcs_features_include_mgt_tools:

Placeholder

  adcs_features: []

Placeholder

  adcs_features: []

Placeholder

  adcs_features: []

Dependencies
------------

None

Example Playbook
----------------

    - hosts: win_servers
      roles:
         - joezollo.adcs

License
-------

WIP

Author Information
------------------

This role was created by Joseph Zollo (joe@zollo.net)
