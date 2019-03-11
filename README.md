# ssh

Ansible role to configure ssh.

For now on, this role handle two configuration parameters :

- PermitRootLogin
- PasswordAuthentication

## Requirements

None.

## Role Variables

Two ! See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add https://github.com/mbocquet/ssh.git roles/ssh`

## Example Playbook

    - hosts: servers
      roles:
         - ssh


    - hosts: servers
      roles:
         - { role: ssh, x: 42 }

## License

GPLv3

## Author Information

http://www.sekoya.org
