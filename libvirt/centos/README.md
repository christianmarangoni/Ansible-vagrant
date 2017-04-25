# Centos

This project creates a distributed filesystem on two servers using [GlusterFS](http://www.gluster.org/).

## Building the VMs

  1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. [Mac/Linux only] Install [Ansible](http://docs.ansible.com/intro_installation.html).
  4. Run `ansible-galaxy install -r requirements.yml` in this directory to get the required Ansible roles.
  5. Run `vagrant up` to build the VMs and configure the infrastructure.

When Vagrant is finished provisioning the VMs with Ansible, run the following two commands to confirm that Gluster is operating nominally:

   

You can also do the following to confirm that files are being replicated/distributed correctly:



## About the Author


