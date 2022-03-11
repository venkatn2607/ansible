Tasks 
play
    1. Install Apache httpd web server
https://docs.ansible.com/ansible/2.5/modules/yum_module.html?highlight=yum
play
    2. Copy index.html to /var/www/html
    https://docs.ansible.com/ansible/2.4/copy_module.html#:~:text=The%20copy%20module%20copies%20a,use%20the%20win_copy%20module%20instead.
play
    3. copy httpd.conf to /etc/httpd/conf/httpd.conf
    https://docs.ansible.com/ansible/2.4/copy_module.html#:~:text=The%20copy%20module%20copies%20a,use%20the%20win_copy%20module%20instead.
paly
    4. start httpd service

    https://docs.ansible.com/ansible/2.3/service_module.html

to run use below

# ansible-playbook webserver.yaml