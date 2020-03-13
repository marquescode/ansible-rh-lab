# A system administrator's guide to getting started with Ansible 
Based on this [tutorial](https://www.redhat.com/en/blog/system-administrators-guide-getting-started-ansible-fast) with some small adaptations for RHEL 8.
### TL;DR: 
1. Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on your control node;
2. Add the private IP of the managed nodes to the /etc/hosts file and name them as "vm2", "vm3 and so on. *E.g. `192.168.1.100 vm2`*;
3. Make sure the ssh is working fine between the control node and the managed nodes; 
3. Use the "hosts" file from this repository as your [ansible inventory](https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html);
4. Run the [playbook](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html) *myplaybook.yml* 😎👍
