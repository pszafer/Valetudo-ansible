# Valetudo-ansible
Install Valetudo automagically with ansible.

## Usage

You need to have localhost in your ansible/hosts file.

- Clone this repository
- Go to roles/valetudo/vars/main.yml
- Edit first 7 variables according to your setup
- Run Ansible

```
ansible-playbook -i valetudo.yml
```

Check out rockrobo_path/flasher_out if everything worked correctly.
