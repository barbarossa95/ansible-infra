# Infra Ansible configuratin by Boba

## Prerequirement

Create and edit `inventory.ini` and `vars/sectets.yml`

## Dry run

```bash
ansible-playbook -i inventory.ini deploy-server.yml --check -e "project-name=<your_project_name_here>"
```

## Run

```bash
ansible-playbook -i inventory.ini deploy-server.yml -e "project-name=<your_project_name_here>"
```
