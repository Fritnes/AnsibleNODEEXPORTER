Node Exporter (node_exporter)
=========

https://github.com/prometheus/node_exporter

Role Variables
--------------

monitoring_tools_folder: Path for store monitoring tools

node_exporter_version: version of Node Exporter

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: node_exporter, when: ansible_system == 'Linux' }

Author Information
------------------

Fritnes (Andrii Tarasenko)
