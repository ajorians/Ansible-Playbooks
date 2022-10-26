## Ansible-Playbooks

First update /etc/hosts with hostnames to match the hosts in inventory.ini

You can use no password or a password

ssh-keygen -b 4048 -t rsa -C "root login" -N ""

# For each machine do this:

ssh-copy-id root@host
