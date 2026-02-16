# Ansible
Exercise repo for ansible automation learning

# Environment preparation
```
$ apt update
$ apt install software-properties-common
$ add-apt-repository --yes --update ppa:ansible/ansible
$ apt install ansible
$ apt install python3-passlib
```

# Example
```
ansible-playbook -i inventory.ini playbooks/tls-for-keycloak.yml
```
