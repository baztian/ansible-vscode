vscode ansible role
===================

![CI](https://github.com/baztian/ansible-vscode/workflows/CI/badge.svg)

Ansible role to install and setup Visual Studio Code.

[Sync Settings
Extension](https://open-vsx.org/extension/zokugun/sync-settings) is
installed.

    > Sync Settings: Open the repository settings

Example Playbook
----------------

    - hosts: servers
      become: yes
      roles:
         - role: baztian.vscode

License
-------

MIT
