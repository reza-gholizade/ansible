# ansible
important script for config management_
create inventory like file " inv " in this repository
# NTP
**change ntp_servers in file ntp/ntp-finall.yml to your ntp servers or domains**
**change hosts value in file ntp/ntp-finall.yml to your host group**
**at last run blew command:**
  - cd ntp 
  - ansible-playbook -i inv ntp-finall.yml
