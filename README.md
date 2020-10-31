# ssh

Ansible role to configure ssh.

For now on, this role handle these configuration parameters :

- PermitRootLogin
- PasswordAuthentication
- GSSAPIAuthentication

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

`git submodule add <clone-url>.git roles/ssh`

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
