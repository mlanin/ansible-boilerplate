### Boilerplate for Ansible project

#### Prepare

Create hosts file for all your environments from example:

```bash
cp hosts.example production
```

Create `group_vars/all.yml` from example:

```bash
cp group_vars/all.example.yml group_vars/all.yml
```

Edit it to match your environment.

#### Use

Playbooks:

- `playbook-example.yml`

```bash
ansible-playbook playbook-example.yml -i production -u root
```
