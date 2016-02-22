mapr_mesos
=========

Install mapr-mesos.

Requirements
------------


Role Variables
--------------


Dependencies
------------

vicenteg.mesosphere

Example Playbook
----------------

    - hosts: mesos_master,mesos_slave
      roles:
         - { role: vicenteg.mesosphere }

License
-------

Apache

Author Information
------------------

Vince Gonzalez
