# Tournament Results Database
 Python module that uses the PostgreSQL database to implement [Swiss-system tournament](https://en.wikipedia.org/wiki/Swiss-system_tournament).

## Prerequisites
- Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- Install [Vagrant](https://www.vagrantup.com/)

## Download the project
- In terminal run `https://github.com/MariiaSurmenok/fullstack-nanodegree-vm.git`

## Start a Virtual Machine
- Change directory to vagrant `cd fullstack-nanodegree-vm/vagrant`
- Run command `vagrant up`. It will start your virtual machine and install all necessary dependencies.
- Log in to your virtual machine from terminal typing `vagrant ssh`

## Run project
- Change directory to tournament folder `cd /vagrant/tournament`
- Create schema for database `psql tournament.sql`
- To run unit tests type `python tournament_test.py`
