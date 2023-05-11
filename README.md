Ansible role: neovim
=========

![Build & Deploy](https://github.com/Provizanta/ansible-role-neovim/workflows/molecule/badge.svg?branch=main)

Install and configure neovim.

Requirements
------------

None

Role Variables
--------------

These variables are set in [defaults/main.yml](./defaults/main.yml):

    neovim_configuration:      # dict, mapping of file paths relative to config dir (key) and its content as string (value)


Dependencies
------------

None

Example Playbook
----------------

    - name: Converge
      hosts: all
      roles:
        - role: neovim
          vars:
            neovim_configuration: {}

License
-------

MIT

Author Information
------------------

Tibor Csóka
