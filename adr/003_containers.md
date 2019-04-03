#Choice of Containers

#Status: Processing

#Context: Assignment 5/6 is to modify a ZMQ example to use Ansible, rather than Docker Compose

#Decision: Ansible is preferred because it runs all containers at once with little configuration. 

3/29/19 Basic ADRs updated. Adjusted playbook code to reflect the docker-compose file.

#Consequences: Ansible isn't favorable to run on Windows machines, making it harder to use cross platform. Docker-compose needs versions to run; with any version updates, it may break the code since it is immutable.