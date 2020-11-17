Setup

    1. Move "inventory" directory and "ansible.cfg" file to /etc/ansible
    2. Specify path to private key in inventories files as well as hosts IP`s.
    3. Run command: 
    # sudo ansible-playbook envs-playbook.yml -l web_servers
