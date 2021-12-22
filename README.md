# Provisioning a LAMP Server using Ansible.

This project provides a LAMP server with a WordPress using as a based distribution Debian and CentOs. 
 
## Steps for this project:
```
- ServerTools
- apache => Install and configure the virtualhost for wordpress.
- php => Provide an php7.3 version
- Mysql => Provide the database for Wordpress and System.
```
Pay Attention:

Before running the playbook, check the hosts file and set the IP configuration according to with own machine.

## Usage
````
root@Ansible:/etc/ansible/LAMP-SERVER-Ansible# ansible-playbook -i hosts ProvisioningLAMPServer.yml
````
