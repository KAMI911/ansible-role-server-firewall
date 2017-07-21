# Ansible Role: IPTabéles Firewall

Travis status:   [![Build Status](https://travis-ci.org/KAMI911/ansible-role-server-firewall.svg?branch=master)](https://travis-ci.org/KAMI911/ansible-role-server-firewall)
Code Climate status: [![Code Climate](https://codeclimate.com/github/KAMI911/ansible-role-server-firewall/badges/gpa.svg)](https://codeclimate.com/github/KAMI911/ansible-role-server-firewall)
Test Coverage status: [![Test Coverage](https://codeclimate.com/github/KAMI911/ansible-role-server-firewall/badges/coverage.svg)](https://codeclimate.com/github/KAMI911/ansible-role-server-firewall/coverage)

## Requirements

None.

## Background
Default server IPTables

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    firewall_init_d_folder: /etc/init.d

Firewall init.d script location

    firewall_init_d_filename: firewall

Firewall init.d script name

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ansible-role-server-firewall

## License

GPLv3

## Author Information

This role was created in 2017 by Kálmán Szalai - KAMI
