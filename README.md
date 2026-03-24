# cyber-playbook

An Ansbile playbook that installs a variety of tools for cybersecurity exercises

## Installing Ansible

```bash
sudo apt install ansible -y
```

## Running the playbook

### Check that packages are installed

Navigate to the `cyber-playbook` folder and run the following command:

```bash
ansible-playbook cyber-playbook.yaml -K
```

### Update existing packages

Navigate to the `cyber-playbook` folder and run the following command:

```bash
ansible-playbook cyber-playbook.yaml -K -e 
```

### 
