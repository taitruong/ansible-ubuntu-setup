# Install ansible
See also: [http://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html](Ansible Installation Guide).

```
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

# Preparations
- disable secure-boot otherwise virtualbox-dkms won't be installed
-- see: https://ubuntuforums.org/showthread.php?t=2393436

# Start 

```
ansible-playbook -K test.yml
```
