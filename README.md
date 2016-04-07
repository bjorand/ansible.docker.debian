# ansible.docker.debian

[![Build Status](https://travis-ci.org/bjorand/ansible.docker.debian.svg)](https://travis-ci.org/bjorand/ansible.docker.debian)

Ansible role to bootstrap a raw Debian Jessie into a Docker host

## Requirements

- Debian Jessie

## Dependencies

None.

## Testing

To test the role in a Vagrant environment just run `vagrant up`.  This will
create a Debian Jessie VMs and it will provision the VM by applying this role with Ansible.

Requires `ansible-playbook` to be in your local path.

## License

MIT


