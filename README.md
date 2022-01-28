# Raspberry Pi Prometheus
## Description
This repository holds the necessary code to setup Prometheus on a Raspberry Pi
## Usage Server
The ansible_hosts file will need to be updated to the host you need to install Prometheus on.  
Then run the following to install.
```
ansible-playbook -i ansible_hosts playbooks/prometheus_server.yml
```
## Usage Node Exporter
To install node exporter run that playbook after editing the node_exporter group in ansible_hosts.
```
ansible-playbook -i ansible_hosts playbooks/node_exporter.yml
```