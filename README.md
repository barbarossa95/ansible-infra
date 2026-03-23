# Infra Ansible configuratin by Boba

## Prerequirement

Create and edit `inventory.ini` and `vars/sectets.yml`

## Dry run

```bash
ansible-playbook -i inventory.ini deploy-server.yml --check
```

## Run

```bash
ansible-playbook -i inventory.ini deploy-server.yml
```
