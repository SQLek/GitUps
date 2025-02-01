# GitUps

My ansible learning project. I'm installing server not very often,
but every time I do it, I have to google how to do it.

I could use notes, but Ansible playbooks could work better than notes.

## Using

Modify `inventory.ini` to your needs.

Create vault with `vault_certbot_email` variable.

```shell
ansible-vault create group_vars/all/vault.yml
```

Run playbook.

```shell
ansible-playbook --ask-vault-pass playbooks/nginx-setup.yml
```