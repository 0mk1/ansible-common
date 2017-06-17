# ansible-docker-xenial

Role to provision ubuntu 16.04.01 LTS (xenial) in that way that it's suitable 
for being host for containers, and node/manager in docker swarm.

```shell
ansible-galaxy install dev-sec.ssh-hardening
```

# Vars

```
custom_ssh_user (default: admin)
custom_ssh_user_password (default: admin)
```
