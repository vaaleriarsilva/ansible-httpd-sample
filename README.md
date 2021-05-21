# ansible-httpd-sample

Open sample to explain a few features of ansible used to install and configure httpd locally.

Files:

main.yml
config.yml

inventories/
    group_vars/
        homolog
        production
    host_vars/
        homolog
        production
    
roles/
   apache_config/
       defaults/
       files/
           file.txt
           index.html
       handlers/
           main.yml
       tasks/
           main.yml
       templates/
           teste_jinja2.html.j2
       vars/
   apache_install/
       tasks/
           main.yml
