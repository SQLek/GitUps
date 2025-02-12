# GitUps

My ansible learning project. I'm installing server not very often,
but every time I do it, I have to google how to do it.

I could use notes, but Ansible playbooks could work better than notes.

## Using

Save `inventory.sample.ini` as `inventory.ini` and modify it to your needs.
Do the same with `host_vars/your-server.local.sample.yml` and save it as `host_vars/domain-or-ip.yml`.

I'm using `lab.sqlek.org` as main website. In future it will be made in more generic way.
To aplay everything run `ansible-playbook playbooks/server-setup.yml`
