# ansible-system_ldap_entries

## Description

[![Galaxy Role](https://img.shields.io/badge/galaxy-system_ldap_entries-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/system_ldap_entries)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-system_ldap_entries.svg)](https://github.com/lotusnoir/ansible-system_ldap_entries/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-system_ldap_entries?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/system_ldap_entries)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/system_ldap_entries)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/system_ldap_entries)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

ldapdd entries into ldap in order to auth with ssh and sudo

## Requirements

you need to install the package python-ldap on the host specified on var ldap_entries_executor


## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: system_ldap_entries
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-system_ldap_entries


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
