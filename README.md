Filebeat role
=========

Роль для установки Filebeat на хостах с ОС: CentOS.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| filebeat_version | "7.16.2" | Параметр, который определяет какой версии filebeat будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: filebeat-role }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
