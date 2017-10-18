# Vagrant Configuration using OpenStack Provider

This is a basic Vagrant Configuration using OpenStack Provider installing docker and Java Oracle 8.

### Requirements
* Vagrant
* OpenStack Server

### Follow the steps

1) Clone the repository
2) Install Vagrant-openstack-provider plugin
```
$ vagrant plugin install vagrant-openstack-provider
```
3) Install Vagrant-Docker-Compose plugin
```
$ vagrant plugin install vagrant-docker-compose
```
4) Install Vagrant-Env plugin
```
$ vagrant plugin install vagrant-env
```
5) Rename the file .env.example to .env and setup your credentials
6) Run
```
$ vagrant up
```
