# Ansible kube-prompt

This is an Ansible project to install the `kube-prompt` golang binary on a
managed system.

## Requirements
This playbook assumes the managed server already has golang installed.

# Usage
Put the host FQDN or IP address of your host in the inventory file and run the
playbook:  

```sh
echo localhost ansible_connection=local >> inventory
ansible-playbook playbook.yml
```
You can also add the remote hosts (with kubectl, kubeconfig and golang) to 
the inventory to configure remote hosts.

