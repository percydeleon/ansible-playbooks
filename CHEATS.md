ansible all -m ping
ansible all -m gather-facts

ansible  all -m apt -a update_cache=true : run apt update

ansible-playbook --ask-become-pass install_apache.yaml
