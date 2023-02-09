# orientDB-instance
sensible playbooks to install orientDB and run its server

This is a simple playbook to install orientDB and run its server. It is based on the official documentation of orientDB and uses a role from Ansible Galaxy.

To run the playbook, you need the following:
 - [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) installed
 - [Docker](https://www.docker.com) installed
 - [ansible-galaxy](https://galaxy.ansible.com) installed 
 - [orientdb role](https://github.com/migibert/orientdb-role) installed `ansible-galaxy install migibert.orientdb`


Then, you can run the playbook with the following command:
```
ansible-playbook -i inventory.yml orientDB.yml
```