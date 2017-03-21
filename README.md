# vagrantFlexSwitchDev
This repository contains vagrant related files needed for setting up base FlexSwitch Development virtual box. THIS SHOULD BE ONLY USED FOR DEVELOPMENT. IF YOU WANT TO RUN FLEXSWICH PLEASE USE DOCKER CONTAINER

Instructions on how to setup Vagrant FlexSwitch resources:

- Make Directory Vagrant (mkdir Vagrant)
- Change Working Directory to Vagrant Directory (cd Vagrant)
- Clone this repository using git clone https://github.com/learnflexswitch/vagrantFlexSwitchDev.git
- Get ubuntu/trusty64 vagrant box by following the steps mentioned on https://atlas.hashicorp.com/ubuntu/boxes/trusty64
- Confirm that you have ubuntu/trusty64 box on your system by executing "vagrant box list" which should display
  "ubuntu/trusty64"
- Change Working Directory to cloned directory (cd vagrantFlexSwitchDev)

Instruction on how to bring up Vagrant Box for development:

1. vagrant up
2. vagrant ssh
        *if asked for password type in: vagrant*
3. cd git
4. Clone OpenSnaproute Repository using git clone https://github.com/learnflexswitch/reltools.git
5. cd reltools
6. fab setupDevEnv

Note:
 - The above mentioned steps assumes that vagrant is already installed by the end user, with VirtualBox as the provider
 - Ubuntu 14.04 is used as base distro for the vagrant developement
 - go 1.5.3 is used
This project is clone from https://github.com/learnflexswitch/vagrantFlexSwitchDev.git 
This project is only for learing purpose.
This project is assumed to be changed by a program. 
DONOT CHECKOUT OR CLONE THIS PROJECT
This project is clone from https://github.com/learnflexswitch/vagrantFlexSwitchDev.git 
This project is only for learing purpose.
This project is assumed to be changed by a program. 
DONOT CHECKOUT OR CLONE THIS PROJECT
