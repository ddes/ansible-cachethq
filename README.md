# ansible-cachethq
Ansible role to deploy CachetHQ status board on Debian/Ubuntu 


Requirements
------------

Just ansible and ssh access on remote machine 


How To Use
----------

Create inventory file or set a host in /etc/ansible/hosts

Then:

ansible deploy.yml -u user


Others
------

Change/adapt following files:

* files/.env
* files/my.cnf
* files/cachet-environment.conf
* files/cachethq.conf



All credits to CachetHQ team, please visit the official WEBSITE:

https://cachethq.io

And github project:

https://github.com/cachethq/cachet
