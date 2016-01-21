# nano-p5-linux-setup

IP Address and SSH port for the P5 Udacity server:

    IP: 52.24.220.58
    Port: 2200

To connect via SSH:

    ssh -i .ssh/udacity_key.rsa grader@52.24.220.58 -p 2200

URL to the project:
    http://52.24.220.58/

Software installed and configuration changes made:

Apache - appropriate settings set to wsgi
PostgreSQL - 'catalog' user created for limited access
Git
pip - Installed relevant packages needed for Catalog App
Catalog App - can be found at https://github.com/TorelTwiddler/item-catalog-vm

`grader` user created with sudo access.
ssh disabled for root.
Firewall set to only allow 2200, http and ntp.
Timezone set to UTC.
