# LEMP INSTALLER BY ANSIBLE PLAYBOOK

I made this for my project to setup Raspberry PI as a PHP Web server based on Raspbian    
The installer will setup all necessary for a Raspberry PI PHP web server (details in bellow)  
  

## What's included
### DBMS
- SQLite3  
- MariaDB with latest version  
*MariaDB will create `admin` account with password `admin` by default*

### Web server
- NGINX with latest version
- PHP-FPM 7.3
- NVM (Node Version Manager) with NPM (Default install latest LTS NodeJS version)
- Memcached

### Web server utilities
- Supervisor
- Cockpit Project (Server monitoring)
- Virtualhost Manage script

### Other utilities
- curl
- git
- vim
- htop
- python3

## How to run

Remotely install
```
ansible-playbook install.yaml -i hosts
```

## Credits
This project inspired by https://github.com/michielgerritsen/ansible-lemp-for-raspberry-pi  
Original Virtualhost Manage Script from https://github.com/RoverWire/virtualhost  
NVM & NodeJS installer by https://gist.github.com/komuw/b3b5d24977d4df7bd549  