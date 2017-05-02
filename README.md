# ansible-rsync
Ansible playbook to rsync a local directory to a remote directory

## Requirements
It's required to have keyfile authentication in the hosts

## Use
To run it, use ansible-playbook

To run it in another host, use the following command
ansible-playbook --private-key=\<identfile\> -u \<connection-user\> -i \<host-ip\>, ansible-rsync.yml
