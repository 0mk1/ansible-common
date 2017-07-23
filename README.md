# ansible-docker-xenial

Role to provision ubuntu 16.04.01 LTS (xenial) to be docker swarm manager/node

```shell
ansible-galaxy install dev-sec.ssh-hardening
```

# Vars

```
custom_ssh_user (default: admin)
custom_ssh_user_password (default: admin)
swarm_init (default: false)

swarm_init_advertise_addr
custom_public_key
```
