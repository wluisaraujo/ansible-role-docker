[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-docker.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-docker)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Docker](https://www.docker.com/)
------------

Description
------------
 * 

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-docker
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
