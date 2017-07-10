Assumptions:
1. Jumpbox with ansible and openstack-clients [ Keystone, Nova, Glance, Neutron, Heat] installed.
2. Tenant RC file is already

Commands:
ansible-playbook -i inventory playbooks/launch_openstack_vm.yml
ansible-playbook -i inventory1 playbooks/main.yml


