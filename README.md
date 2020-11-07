role-tools
=========
> Simple codebase role

Install tools and dependencies for them : `go`, `nodejs`

Requirements
------------

Linux Ubuntu / Debian machine

Role Variables
--------------
#### Needed

Check [defaults/main.yaml](./defaults/main.yml)

Dependencies
------------

No

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: role.tools, node_version: latest }

License
-------

BSD

Author Information
------------------

[Loic Roux]()
