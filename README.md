role-tools
=========
> Simple codebase role

### TO DO
- [ ] adjust already installed checks for faster role exec

Install tools and dependencies for `go`, `nodejs`, `yarn`, `python` and system packages

- For `go` is used : [g](https://github.com/stefanmaric/g)
- For `node` is used : [n](https://github.com/tj/n)

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
