Use `ansible-playbook main.yml --ask-vault-pass`

inventory is an .ini file formated as such:

```
[vps]
vps1 ansible_become_password=vps1pass
vps2 ansible_become_password=vps2pass
```