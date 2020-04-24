ansible-prom-reports
=========

Деплоит в Docker скрипты и веб-интерфейс для составления отчета о недоступности устройств, взятого из API Prometheus'a. 

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should
be mentioned here. For instance, if the role uses the EC2 module, it may be a
good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

[Docker](../../docker-playbook.yml)

Example Playbook
----------------

Роль уже  включена в плэйбук docker-playbook
    - hosts: servers
      roles:
         - { role: ansible-prom-reports, x: 42 }

License
-------

BSD

Author Information
------------------

Dmitry Bubnov
[Telegram](https://t.me/bubnov)


