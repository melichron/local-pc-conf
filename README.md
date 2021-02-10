# Usage

First clone repo, then `cd` to it.

Install Ansible:
```
sudo apt update && sudo apt install ansible -y
```

User have to be able execute command with sudo without password. Simply:
```
echo "$USER		ALL = (ALL) NOPASSWD:ALL" | sudo tee /etc/sudoers.d/$USER
```
for executing `sudo` commands without password.

Finally, execute playbook:
```
ansible-playbook local-pc-conf.yml
```
and wait.
