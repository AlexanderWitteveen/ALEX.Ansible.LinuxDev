# Ansible Collection - alex.linuxdev collection
Documentation for the collection.

# Install
ansible-galaxy collection install git+https://github.com/AlexanderWitteveen/ALEX.Ansible.LinuxDev.git

# Use playbook
vars="{\"args_dhcpipaddress\":\"hostip\"}"  
export ANSIBLE_CONFIG=/etc/ansible/ansible.cfg  
ansible-playbook alex.linuxdev.rebuildvm -vv --extra-vars "$vars"  
