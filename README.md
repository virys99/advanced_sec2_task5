# advanced_sec2_task5
Apply playbook by those commands:

For production:

ansible-playbook -i inventories/prod playboks/site.yaml --ask-vault-pass

For dev:

ansible-playbook -i inventories/dev playboks/site.yaml --ask-vault-pass

Ansible vault contains variables:
---
ansible_user

ansible_password

ansible_become_password
