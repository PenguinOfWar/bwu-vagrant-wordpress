# bwu-vagrant-wordpress
A simple Vagrant recipe to provision a blank WordPress install, using Ubuntu 16.04, NGINX, PHP 7.0 and MariaDB 

## Prerequistes

- Vagrant - https://www.vagrantup.com/
- The `puppetlabs/ubuntu-16.04-64-puppet` Vagrant image

Note: Ubuntu 16.04 seems to not like older versions of Vagrant. This was tested with 1.9.5.

## Install

1. `git clone https://github.com/PenguinOfWar/bwu-vagrant-wordpress.git`
2. `cd bwu-vagrant-wordpress`
3. `vagrant up`
4. Visit `http://192.168.2.10` in your browser
5. Follow the instructions, your database is called `mysql` and the username and pasword are both `vagrant`
6. Configure your site details
7. Done!