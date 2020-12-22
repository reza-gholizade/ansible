# NTP
1- create inventory like file " inv " in this repository

2- change ntp_servers in file ntp/ntp-finall.yml to your ntp servers or domains

3- change hosts value in file ntp/ntp-finall.yml to your host group

4- at last run blew commands:

``` 
~$ cd ntp 
~$ ansible-playbook -i inv ntp-finall.yml
```
# zabbix
1- create inventory like file " inv " in this repository

2- change hosts value in file ansible-zabbix-agent.yml to your host group

3- change remote_user in file ansible-zabbix-agent.yml to your reomte user

4- change  variable zabbix_server in file ansible.zabbix-agent.yml to your zabbix server IP

5 - at last run blew commands:
```
~$ cd zabbix 
~$ ansible-playbook -i inv ansible-zabbix-agent.yml 
```
