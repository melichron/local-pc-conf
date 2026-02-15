# Usage

First clone repo, then `cd` to it.

Install Ansible:
```
sudo apt update && sudo apt install ansible -y
```

User have to be able to execute command with sudo without password. Simply:
```
echo "$USER		ALL = (ALL) NOPASSWD:ALL" | sudo tee /etc/sudoers.d/$USER
```
for executing `sudo` commands without password.

Finally, execute playbook:
```
ansible-playbook local-pc-conf.yml
```
and wait.

Or install only `oh-my-zsh` with script with `curl`

```shell
curl -fsSL https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash
```
or `wget`

```shell
wget -qO- https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash
```

For setup and install `tmux`:

```shell
curl -fsSL https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- tmux
```
or `wget`

```shell
wget -qO- https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- tmux
```

For setup and install `screen`:

```shell
curl -fsSL https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- screen
```
or `wget`

```shell
wget -qO- https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- screen
```

For setup and install `bash-it`:

```shell
curl -fsSL https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- bash-it
```
or `wget`

```shell
wget -qO- https://raw.githubusercontent.com/melichron/local-pc-conf/refs/heads/master/install-oh-my-zsh.sh | bash -s -- bash-it
```
