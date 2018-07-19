uclalib_role_uclalibrepo
=========

This Ansible role configures a RHEL system to use the UCLA Library's local yum repo.

Role Variables
--------------

Default variables for this role that can be overridden if needed:

    repo_url - defines the URL where the uclalib repo is hosted

    repo_file - defines the file system path where the repo is configured


Example Playbook
----------------

A simple example playbook that uses this role:

    ---

    - hosts: all

    roles:
      - { role: uclalib_role_uclalibrepo }

License
-------

BSD 3-Clause
