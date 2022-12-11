# Key pair and Vault

- Create a files directory which will contain a secrets folder which will contain a credentials.vault file
- Move the variable containing the admin password variable into this file
- Then you will encrypt this file with the ansible-vault encrypt command
- You will modify the playbook deploy.yml to ask it to load the vault file as vars_files
- Generate a key pair (ssh-keygen -t rsa) leaving all parameters as default
- Copy the contents of the public key (id_rsa.pub) to the client's /home/admin/.ssh/authorized_host file
- Modify the inventory file to add this variable to all hosts (all) ansible_ssh_common_args='-o StrictHostKeyChecking=no
- Start your playbook by adding the parameter that will allow you to provide the vault key
- Check that everything went well
- In order to keep your work, push it on your github
# wordpress-ansibele
# wordpress-ansibele
