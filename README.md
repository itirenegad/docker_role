Role Name
=========
After variabilizing the hostnames of remotes hosts, we have prepared a playblook that thanks to the docker role, installs docker on our machines and according to the distribution Ubuntu or CentOS. We also install the prerequisites so that remotes can manage the life cycle of the containers that will deploy.

Requirements
------------

Ubuntu or CentOS Linux distribution.

Role Variables
--------------

We use the hostname and distribution to run this playblook.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: 
        - servers
      roles:
        - role: itirenegad.docker_role

License
-------

license (GPL-2.0-or-later, MIT, etc)

Author Information
------------------

Learning from Sado Frazer.
