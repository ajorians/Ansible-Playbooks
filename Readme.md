## Ansible-Playbooks

First setup access to the host by adding it to: /etc/ansible/hosts

You can use no password or a password

ssh-keygen -b 4048 -t rsa -C "root login" -N ""

# For each machine do this:

ssh-copy-id root@192.168.0.60
