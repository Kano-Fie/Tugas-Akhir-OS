# Final Project SO S3
Tugas Akhir Sistem Operasi
SSH SERVER dan WEB SERVER

# Machine
- CPU		: Intel G4560
- Memory	: 16GB
- Storage	: 500GB
- OS		: Ubuntu 22.04, Windows 11 Pro, Centos 7

# SSH Server
## Installasi dan Konfigurasi SSH Server
Install OpenSSH Server
- sudo apt update
- sudo apt install openssh-server

## Ubuntu-22.04-Web-Server-Setup
## Using nginx, php, mariadb, and adminer.php to setup a web server.
Describes the linux commands needed to set up a web server on ubuntu 22.04
We start from the idea that you already have an ssh file private key to connect to the ubuntu server as root user where you will carry out the installation.

Note: As is obvious and expected, some words like: your_server_ip, your_ssh_file, your_port, your_domain, your_new_user, dbAdmin, your_db_password and others can or should be replaced with your server connection information or data. I hope you have already purchased a domain from amazon aws, godaddy, digitalocean or any other dns or web hosting provider. And they have already provided you with all this information with which to replace the words said above. Of course, the password for your ubuntu user and mysql (mariaDB) user will have to be decided by you. This is not going to be given to you by any web service provider.
