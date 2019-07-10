# Ansible

 
## hosts in directory ansible
    
    [client]
    172.16.4.155

## main.yml in directory ansible
    ---
    - hosts: client
      roles: 
        - apache
## Run
      ansible-playbook main.yml 
