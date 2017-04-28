# ansible-rsync
Ansible playbook to rsync a local directory to a remote directory

## Use
To run it, use ansible-playbook.

To run it in another host, use the following command.
ansible-playbook --private-key=<identfile> -u <connection-user> -i <host-ip>, rsync.yml
