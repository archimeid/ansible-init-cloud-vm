# ansible-init-cloud-vm

This playbook allows you to set same password on each VM listed in hosts file during your first login attempt. It then deploys your public key to each VM.

This playbook has been tested with VMs running Ubuntu 20.04 Focal Fossa LTS.

## Hosts file

Example :

vm_hostname_or_ip old_password="old_password" ansible_user="ansible_user"