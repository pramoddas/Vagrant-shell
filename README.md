#  Vagrant With Shell Provisioning

## Instructions

We expect you to be familiar with [git][1], [Vagrant][2] and [VirtualBox][3].


Please make sure you update the provisioner in case your application requires extra packages, database
schema changes, code/dependencies initialization or service startup.

* `git clone <this repository url>`
* `vagrant up --provision`


## Scripts

Provisioner: basch script to install all the dependent sofware components
apache, php, redis and mysql and dependencies are installed

The provisioner reads the host.conf to set the virtual host configurations and populate_db to seed
test data in the database.

## Dependencies
  [1]: http://git-scm.com/
  [2]: https://www.vagrantup.com/
  [3]: https://www.virtualbox.org/
