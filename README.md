# ansible-ops-manager
Ansible role to install MongoDB Ops Manager__
This will run a standalone mongod as application database. Then download, install, and configure Ops Manager.

### Access
Username: opsmanager@expedia.com __
Password: <contact holee@expedia.com>

### Example play
install_opsmanager.yml
```
- name: opsmanager
  hosts: all
  become: yes
  gather_facts: yes
  roles:
    - ansible-ops-manager
  vars:
    mongodb_ops_manager_binary: https://downloads.mongodb.com/on-prem-mms/rpm/mongodb-mms-3.4.10.547-1.x86_64.rpm
```

### Example ansible-playbook command
```
tbd
```
