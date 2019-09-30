[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-Docker-blue.svg)](https://galaxy.ansible.com/wluisaraujo/docker) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-docker.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-docker)

---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [Docker](https://www.docker.com/)
------------

Description
------------
 * 

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.docker
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.docker/requirements.txt
```

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
    - docker
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)