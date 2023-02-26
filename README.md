This project installs a glusterfs cluster on remote servers specified in the hosts file.

### Notes:
* You need to install community.general collection.
  ```
  ansible-galaxy collection install community.general
  ```


```
ansible-playbook -i hosts glusterfs.yml 
```
* Add IP adresses of the target nodes to the hosts file. 
* Add your key to /vars/main.yml to make ssh connections without passwords. The one provided in the file is a dummy key.
* 
