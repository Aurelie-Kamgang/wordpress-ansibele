# Deploy wordpress with ansibles roles

- Create a cluster (1 ansible and 1 client) 
- Create a wordpress.yml playbook to deploy wordpress (as a docker container) on the client
docker container) on the client using the following role:
https://github.com/diranetafen/ansible-role-containerized-wordpress.git
- Run the playbook and check that it works like a charm and that you have
you have wordpress (you can expose wordpress on the external port of your choice
of your choice, 80 or 8080 or whatever, as long as it is not already being used on your
on your client machine by another container)

