# ansible
important script for config management_
create inventory like file " inv " in this repository
# NTP
1- change ntp_servers in file ntp/ntp-finall.yml to your ntp servers or domains

2- change hosts value in file ntp/ntp-finall.yml to your host group

3- at last run blew command:
``` 
~$ cd ntp 
~$ ansible-playbook -i inv ntp-finall.yml```
