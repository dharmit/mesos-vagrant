mesos-vagrant
=============
Deploys Mesos cluster with a simple `vagrant up` command. Uses
[ansible](https://github.com/ansible/ansible) for provisioning


Features
--------
- [X] Deploy single-node mesos-cluster on *virtualbox* and *digitalocean*
  providers
- [X] Install and start Marathon framework
- [X] Enable [Docker](https://github.com/docker/docker) containerizer for Mesos
  slave
- [ ] Deploy multi-node mesos-cluster on *virtualbox* and *digitalocean*
  providers


Good to have
------------
- [ ] Support for more providers


Usage
-----
Simply `cd` into a directory and do `vagrant up`. Ideally, refer the README in
respective directories as well.
