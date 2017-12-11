# Ansible Vagrant 

Vagrant & Ansible Template for Lab

## Description

Virtual machine for different hypervisor with vagrant 



## Requirments for Infrastructure

  1. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).
  2. Download and install [Vagrant](http://www.vagrantup.com/downloads.html).
  3. [Mac/Linux ] Install [Ansible](http://docs.ansible.com/intro_installation.html).
  3. [windows wit wsl  ] Install [Ansible](http://docs.ansible.com/ansible/latest/intro_windows.html#using-a-windows-control-machine).
  


 


## VMs/Apps Currently Present

 TBD

### WSL Enviroment ####

Enable WSL 
https://msdn.microsoft.com/en-us/commandline/wsl/install-win10

Install Vagrant on wsl 

https://www.vagrantup.com/docs/other/wsl.html

Windows Access 
export VAGRANT_WSL_ENABLE_WINDOWS_ACCESS="1"

add thi step 

Install Vagrant and check if you can run the windows native VirtualBox cli tool.
sudo apt-get install Vagrant export PATH=$PATH:"/mnt/c/Program Files/Oracle/VirtualBox" VBoxManage.exe

Since vagrant requires the executable to be called VBoxManage, I've linked it at /usr/bin
sudo ln -s "/mnt/c/Program Files/Oracle/VirtualBox/VBoxManage.exe" /usr/bin/VBoxManage VBoxManage



