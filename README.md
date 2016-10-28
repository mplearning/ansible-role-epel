EPEL
====

Adds the EPEL repository to YUM on Enterprise Linux 7, and installs the `epel-release` package on CentOS.

Requirements
------------

Ansible 1.9 is the minimum supported.

Role Variables
--------------

No additional variables are used.

Dependencies
------------

No external dependencies are required.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ucsdlib.epel

License
-------

BSD 2 Clause

Author Information
------------------

John H. Robinson, IV  
The Library  
UC San Diego  
