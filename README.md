# ansible-demo-VmugPNQ

This ansible playbook will help to deploy vmware guest on VMware vCenter Server.

# To deploy the VM:

$ ansible-playbook deploy-vmware-guest.yaml

# Following Steps will be performed:
- Create a VM folder
- Create a Resource Pool
- Deploy the VM
- Map the IP and Configure the FQDN


# To delete the VM:

$ ansible-playbook delete-vmware-guest.yaml

# Following Steps will be performed:
- Take the input of VM name
- Delete the VM
- Delete the VM Folder
- Delete the Resource Pool
