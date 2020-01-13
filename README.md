# ANSIBLE LEMP INSTALLER


## What's included
### DBMS
- MariaDB with latest version
- SQLite3

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

## How to run

```
ansible-playbook install.yaml -i hosts
```

## Credits
Inspired by https://github.com/michielgerritsen/ansible-lemp-for-raspberry-pi  
Virtualhost Manage Script https://github.com/RoverWire/virtualhost  
NVM & NodeJS installer by https://gist.github.com/komuw/b3b5d24977d4df7bd549  