Ansible Role to install a Zabbix Server 5.0
----

How to use
----

1 - Inventory:

Configure the hosts file with `zabbix server IP` and `ssh user/password`


2 - Default variables:

In the file: `/roles/zabbix/defaults/main.yml` set you zabbix data


3 - Running

`ansible-playbook -i hosts playbook.yml`