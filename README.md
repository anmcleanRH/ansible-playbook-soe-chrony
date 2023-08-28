SOE-Chrony
=========

This playbook is a conversion of a role that will ensure chrony is installed and will set the NTP servers using the chrony.conf.j2 template.  It will set the timezone to UTC (or whatever you would like to set it as)

Requirements
------------


Role Variables
--------------
ntp_server_name1,2, and 3 need to be specified in the roles/ansible-role-soe-chrony/vars/main.yml file

Dependencies
------------

Example Playbook
----------------

License
-------

BSD

Author Information
------------------

Andy Mclean

