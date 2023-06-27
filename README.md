# This is an Ansible repository for wordpress

# What this repository contains
1. common(yum update,swap,SELinux,firewalld,hostname,Timezone,useradd) 
2. httpd
3. MySQL
4. PHP
5. WordPress

# How to run
1. Copy private key to a file in kyes directroy 
2. Change group_vars,user,Keys,playbook.yml,hosts,vhosts
3. Dry run with "ansible-playbook --private-key {PATH} -i {PATH} hosts {PATH} -C"
4. Run with "ansible-playbook --private-key {PATH} -i {PATH} hosts {PATH}"

# Check
1. Visit http://[Domain name]
2. Set up WordPress configuration
