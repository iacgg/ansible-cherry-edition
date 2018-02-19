## Welcome to my Ansible - cherry edition!

Everything in this repository is ONLY used for testing.
Nothing is used in ANY production environment

Following [Ansible best practice](https://docs.ansible.com/ansible/latest/playbooks_best_practices.html) V2.4

###	For the H5 "datacenter"

#### VM settings in virtualbox enviroment

- Adapter 1: NAT (Static ip configuration)

Bootstrap

`$ ansible-playbook -i inventories/H5/virtualbox  bootstrap.yml  -u bootstrap -k -K`

The bootstrap roles install python and python-apt, so ansible with or without check mode can be used


