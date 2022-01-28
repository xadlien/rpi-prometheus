# Raspberry Pi Prometheus
## Description
This repository holds the necessary code to setup Prometheus on a Raspberry Pi
## Usage
The ansible_hosts file will need to be updated to the host you need to install on.  
Then run the following to install.
```
ansible-playbook -i ansible_hosts playbooks/prometheus_server.yml
```