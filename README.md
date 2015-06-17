CloudStack
==========

Install and Update Apache CloudStack.

Requirements
------------

TBD

Role Variables
--------------

TBD

Dependencies
------------

None

Example Playbook
----------------

    - hosts: cloudstack-db
      roles:
         - { role: resmo.cloudstack, type: acs-db }

    - hosts: cloudstack-management
      roles:
         - { role: resmo.cloudstack, type: acs-management }

    - hosts: cloudstack-hosts-kvm
      roles:
         - { role: resmo.cloudstack, type: acs-host-kvm }

    - hosts: cloudstack-hosts-xen
      roles:
         - { role: resmo.cloudstack, type: acs-host-xen }

License
-------

Apache License, Version 2.0

Author Information
------------------

René Moser <resmo@apache.org>
