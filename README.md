ossec-agent
===========

[![Build Status](https://travis-ci.org/diadzine/ansible-ossec-agent.svg?branch=master)](https://travis-ci.org/diadzine/ansible-ossec-agent)

Ansible role to install the wazuh ossec-agent.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

```
ossec_server_ip: "127.0.0.1"
```

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: diadzine.ossec-agent, ossec_server_ip: 111.111.111.111 }

License
-------

MIT License.

Author Information
------------------

This role was created in 2017 by [Aymeric Bringard](https://github.com/diadzine/).
