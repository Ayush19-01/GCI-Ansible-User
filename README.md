# GCI-Ansible-User
### How to create user with this Ansible Role

1. Download or clone the repository.

2. Open the playbookcreate.yml file and change:
    
     1. remote_user to your current user
     
     2. username to the name that the new user would have(It should be a valid Linux username)
     
     3. password to the password you want to create for the new user

3. Open terminal in the directory where playbookcreate.yml is present, run the following command in the terminal
    
    `$ sudo ansible-playbook playbookcreate.yml`
    
4. To log in the user you just created from the terminal type
    
    `$ sudo su - username`
 
5. The above command would give you access to the terminal as the newly created user.

6. Type `exit` to logout from the user     
