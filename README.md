# NTP
1- create inventory like file " inv " in this repository
2- change ntp_servers in file ntp/ntp-finall.yml to your ntp servers or domains
3- change hosts value in file ntp/ntp-finall.yml to your host group
4- at last run blew commands:
``` 
~$ cd ntp 
~$ ansible-playbook -i inv ntp-finall.yml
```
