# Ansible Vagrant 

Vagrant & Ansible Template for Lab, For Building Code

## Description

This repository contains a collection of example virtual machines running various applications. The VMs are created via Vagrant and provisioned via Ansible.

You can `cd` into any of the included directories and run `vagrant up`, and a generic Linux VM will be booted and configured in a few minutes. You just need to install [Vagrant](http://vagrantup.com/), [VirtualBox](https://www.virtualbox.org/), and [Ansible](http://www.ansible.com/). View the included README.md file in any of the subdirectories to find out more about the particular VM.

All of these examples use a combination of [roles I've added to Ansible Galaxy](https://servercheck.in/blog/using-ansible-galaxy), and were created to help demonstrate Ansible's simplicity and flexibility.

Read more about Ansible and how I use it to manage infrastructure in [Ansible for DevOps](http://ansiblefordevops.com/), a book I've written.

## Requirments for Infrastructure

  1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. [Mac/Linux only] Install [Ansible](http://docs.ansible.com/intro_installation.html).
  4. Run `ansible-galaxy install -r requirements.yml` in this directory to get the required Ansible roles.


## VMs/Apps Currently Present

  - **Centos** (`Centos 7` - Base Centos 7 with firewall Option).
  