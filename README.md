# Valetudo-ansible
Install Valetudo automagically with ansible on mac

## Usage

- Clone this repository
- Go to roles/valetudo/vars/main.yml
- Edit first 7 variables according to your setup
- Do the same for roles/flash/vars/main.yml
- Install virtualbox + ubuntu

1. (on ubuntu)
```
ansible-playbook build.yml
```
After that is finished make sure the folders match up

2. (on macOS)
```
ansible-playbook flash.yml
```

Check out rockrobo_path/flasher_out if everything worked correctly.

idea from @pszafer
