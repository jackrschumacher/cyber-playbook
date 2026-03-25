# cyber-playbook

An Ansbile playbook that installs a variety of tools for cybersecurity exercises

## Installing Ansible

```bash
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y
```
## General commands

`-v, -vv, -vvv` - Increasing levels of verbosity in the terminal


## `install-packages.yaml`

### Check that packages are installed

Navigate to the `cyber-playbook` folder and run the following command:

```bash
ansible-playbook playbooks/install-packages.yaml -K -l "rpi5-8"
```

### Update existing packages

Navigate to the `cyber-playbook` folder and run the following command:

```bash
ansible-playbook playbooks/install-packages.yaml -K -e "app_state=latest" -l "[host]"
```

### `cyber-repositories.yaml`
