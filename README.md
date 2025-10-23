# Ansible Automation Playbooks

To run the playbook(s), you will need:
- Python > 3.0
```
sudo apt-get install python -y
``` 
  - make sure pip is installed
```
python3 -m pip -V
```
- Ansible
```
pipx install --include-deps ansible
```
  - the --include-deps flag just ensures that any deps Ansible needs, it installs
---
### Running the Playbook(s):
To run any playbook the command is as follows:
```
ansible-playbook -i <inventory_filename> <playbook_name> 
```
Now, watch the magic happen!

[Documentation](https://docs.ansible.com/ansible/latest/)

