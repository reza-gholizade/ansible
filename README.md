# ansible
important script for config management_
create inventory like file " inv " in this repository_
# NTP
- change ntp_servers in file ntp/ntp-finall.yml to your ntp servers or domains_
- change hosts value in file ntp/ntp-finall.yml to your host group_
- at last run blew command:_
  - cd ntp 
  - ansible-playbook -i inv ntp-finall.yml
