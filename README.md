# Ansible Role: Redis

Installs Redis on RHEL/CentOS 6.x.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - geerlingguy.repo-epel

## Example Playbook

    - hosts: all
      roles:
        - { role: geerlingguy.redis }

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](http://jeffgeerling.com/), author of [Ansible for DevOps](http://ansiblefordevops.com/).