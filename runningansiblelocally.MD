## the follwoing play will run loaclly
---
- hosts: all \
  tasks: 
    - shell: echo "Hello Kiran"

ansible-playbook -i "localhost," -c local sayhello.yml
