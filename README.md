fonts
=====

Install fonts on Ubuntu desktops from the `files/` directory and rebuilds the fonts cache.

Please be aware that the fonts have to be licensed and this role should only be used internally.

Requirements
------------

None

Role Variables
--------------

Configure the file list `fonts_files` in `vars/main.yml`.


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Marc Urben

