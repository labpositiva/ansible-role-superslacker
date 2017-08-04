# Ansible Role Superslacker

[![Build Status](https://travis-ci.org/labpositiva/ansible-role-superslacker.svg)](https://travis-ci.org/labpositiva/ansible-role-superslacker)
[![Stories in Ready](https://badge.waffle.io/labpositiva/ansible-role-superslacker.svg?label=ready&title=Ready)](http://waffle.io/labpositiva/ansible-role-superslacker)
[![GitHub issues](https://img.shields.io/github/issues/labpositiva/ansible-role-superslacker.svg)](https://github.com/labpositiva/ansible-role-superslacker/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)


Installs and configures [superslacker][link-superslacker] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - none


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for superslacker


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - superslacker

To install a specific version:

    - hosts: servers
      roles:
         - { role: labpositiva.superslacker }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-luis]
- [All Contributors][link-contributors]


<!-- Other -->

[link-superslacker]: https://github.com/MTSolutions/superslacker
[link-luis]: https://github.com/luismayta
[link-contributors]: contributors
