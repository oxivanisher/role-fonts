fonts
=====
[![Ansible Lint](https://github.com/oxivanisher/role-fonts/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-fonts/actions/workflows/ansible-lint.yml)

Install fonts on Linux desktops from the `fonts_src_dir` directory and rebuilds the fonts cache.

Please be aware that fonts have to be licensed correctly.

Requirements
------------

None

Role Variables
--------------

| Name          | Comment                                        | Default value                     |
| ------------- | ---------------------------------------------- | --------------------------------- |
| fonts_src_dir | Source directory of the fonts to be installed. | `{{ playbook_dir }}/files/fonts/` |

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- name: Install desktop fonts
  hosts: clients
  roles:
    - role: oxivanisher.linux_desktop.fonts
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_desktop](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_desktop/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_desktop).
