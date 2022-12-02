# WordPress Provision through Ansible Playbook.

## Description:

A simple wordpress site provision through ansible-playbook. Furthermore, the ansible playbook is installed in complete packages like the lamp. Also, you can create multiple WordPress sites with appending your decision. In addition, the playbook is basically designed for ubuntu 20.04, and it's using Nginx.

It's just a try for application provision through ansible. Maybe it has bugs with other Debian distributer. So please let me know if you have to face any issues while using this then I will help you to figure out and correct the issue. So, please ping me via linked that would be more helpful to correct if any bugs you got.

## Features:

- Easy to create wordpress sites on ubuntu (with the help of nginx)
- Domain name, wordpress databases, password is appending your descision. you don't needs to edit in core files who used this.
- All the components are installed through the playbook like (Nginx, MySQL, PHP, Wordpress)

## Components and Resources:

- Ubuntu 20.04 (Ansible-Client)
- Nginx (Used webserver)
- PHP and dependencies
- MySQL
- WordPress 5.7
- Ansible2 (Ansible-Master. Please note that I have used master server is RedHat Distributer "amazon-linux")
