# Intro
This role sets up udev rules and ensures that they're active.

## Requirements
While there's no explicit dependency roles, the target machine should be able to act as a Docker host.  The `geerlingguy.docker` Ansible role is a suitable solution.

## Role Variables
See the [comment in the default variables file](defaults/main.yml) for information on configuration.

## Dependencies
None.

## Example Playbook
    - hosts: whatever
      roles:
        - triplepoint.udev_rules

## License
MIT
