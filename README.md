# ansible-common

### vars

```
sudo_user:
  (default: admin)

sudo_user_password:
  (default: admin)

install_utils_packages:
  (default: ['vim', 'htop', 'tmux'])

disabled_services:
  (default: ['accounts-daemon', 'snapd', 'snapd.system-shutdown', 'snapd.autoimport', 'pollinate', 'lxd-containers', 'lxcfs'])

sudo_user_public_key:
  (optional)
```
