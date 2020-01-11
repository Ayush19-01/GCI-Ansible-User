# GCI-Ansible-User
### How to create user with this Ansible Role

1. Download or clone the repository.

2. You need a hashed password to run the role successfully, run the following command on the terminal to get a hashed password

                `python -c 'import crypt; print (crypt.crypt("insert your password here"))'`

2. Open the createusers.yml file and change remote_user to your current user

3. Open the main.yml file and change the username to your choice and password to the one that got from the above command.

4. Open terminal in the directory where createusers.yml is present, run the following command in the terminal
    
    `$ sudo ansible-playbook createusers.yml`
    
5. To log in the user you just created from the terminal type
    
    `$ sudo su - username`
 
6. The above command would give you access to the terminal as the newly created user.

7. Type `exit` to logout from the user     

### Screenshot

![alt text](https://github.com/Ayush19-01/GCI-Ansible-User/blob/master/Screenshot%20from%202020-01-11%2019-35-57.png)
