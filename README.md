# ansible
clone project and run script 

## Install ansible
```
sudo apt-add-repository -y ppa:ansible/ansible
sudo apt-get update -y
sudo apt-get install -y curl git software-properties-common ansible
```

## Run script
```
ansible-playbook -t install local.yml --ask-become-pass --ask-vault-pass
```