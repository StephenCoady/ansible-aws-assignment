# Ansible AWS Provisioning

This assignment is to show how ansible can be used to provision a web infrastructure consisting of 1 HAProxy web server and as many nginx servers as the user wishes. It aims to show how ansible vault can also be used to encrypt variables.

## Running the playbook

To run this playbook use the following command:

```sh
ansible-playbook -e "nginx_count=2" playbooks/create-infrastructure.yml --vault-password-file vault_password.txt
```
