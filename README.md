# GCI-Ansible-User
### How to create user with this Ansible Role

___The playbook file in this repo is a demo file, just to run the role, the role exists inside sample.users___

1. Download or clone the repository.

2. Open the createusers.yml file and change remote_user to your current user, username and password of your choice


4. Open terminal in the directory where createusers.yml is present, run the following command in the terminal
    
    `$ ansible-playbook -K createusers.yml`
    
5. To log in the user you just created from the terminal type
    
    `$ sudo su - username`
 
6. The above command would give you access to the terminal as the newly created user.

7. Type `exit` to logout from the user     

### Screenshot

![alt text](https://github.com/Ayush19-01/GCI-Ansible-User/blob/master/Screenshot%20from%202020-01-11%2019-35-57.png)
