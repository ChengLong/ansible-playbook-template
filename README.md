Ansible Seed
---

This is a seed to get you started using Ansible to config your machines. 

Usage
---

1. Config hosts in `inventory.ini`. Note, it's important that you set `ansible_ssh_private_key_file`, `ansible_ssh_user`, `ansible_sudo_pass` correctly. 
2. Write playbook `playbook.yml`. Get roles from [here](https://galaxy.ansible.com/list#/roles) 
3. Run `ansible-playbook playbook.yml`

License
---

[WTFPL](http://www.wtfpl.net/)
