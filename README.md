oracle-install-lock
=========

Role to determine if current host is the master in RAC cluster and could perform the initial software install.

This role is part of full Oracle RDBMS home management solution:
https://github.com/ilmarkerm/ansible-oracle-home-mgmt

Requirements
------------

Oracle Grid Infrastructure or Oracle Restart is required

Role Variables
--------------

Role sets fact oracle_install_lock_granted (boolean)
Role uses facts oracle_rac and oracle_rac_master_host that should be defined with cluster group_vars

Example Playbook
----------------

Check out playbook and full Oracle RDBMS home management solution example here: https://github.com/ilmarkerm/ansible-oracle-home-mgmt

License
-------

Apache 2.0

Author Information
------------------

Ilmar Kerm, ilmar.kerm@gmail.com
https://ilmarkerm.eu
