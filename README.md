Ansible Role: phalcon
=====================

phalcon build from source

Requirements
------------

None.

Role Variables
--------------

- `phalcon_work_dir`
    - fetch and build source work dir
- `phalcon_version` (require)
    - build version
    - e.g: 3.0.1

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      vars:
        phalcon_version: 3.0.1
      roles:
         - tyoshii.phalcon

License
-------

BSD, CC-BY
