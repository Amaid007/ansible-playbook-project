# ansible-playbook-project

##Ansible Docker Deploy

This repository contains an Ansible playbook to deploy an Apache Docker container and configure, used subnet

### Set up

i am running ubuntu desktop (setting used network bridge for this) on my virtual machine using oracle virtualbox in my Windows 11 pro

1. Host Machine: For me, it is the machine where VirtualBox is located in your computer.

2. Control Machine: This is the machine where Ansible is installed and through which you manage your Ansible Playbooks you execute. In your case, this is the Ubuntu desktop running in the VirtualBox as the base computer platform from which the new systems can be configured. 

3. Target Machine: it could be another virtual machine or container maintained by you Ubuntu desktop, (Control Machine).

#### Create/sign in github account

make a public Respositary with decent namr & check mark README.me 

##### installation git/Ansible/docker

1. config git with username & email
2. use command  git clone for making a connection between your local repository to github/ git remote
3. git add, commit & push  command to add, push files to directory.
4. install Ansible & check version after installation
5. install docker,io you need to log out after installing and back login for final touches.

###### create playbook in local repository 

after changing cd repository name.
1. Use touch command for creation
2. nano for pop up to edit this playook like  touch playbook.yml / nano playbook.yml

####### inventory/host

inventory or host file created and edit same like playbook file for configuration

####### docker

1. Install
2. start service
3. add user to docker
4. permissions

######## run asible playbook

######### Errors

few Errors came. you have to tackle those  Errors with courage dont be like deer in the headlights.


