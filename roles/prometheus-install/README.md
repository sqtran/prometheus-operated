Role Name
=========

This role installs the Community Prometheus operator, and sets up a sample Service Monitor that looks at spring-boot actuator endpoints.

Requirements
------------

Needs a running OCP 4.x cluster

Role Variables
--------------

No variables.

Dependencies
------------

No dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - role: prometheus-install

License
-------

BSD

Author Information
------------------

Steve Tran
