# Install PiHole 6 Beta on a fresh bare metal system / VM

## Why?
For easy testing, on a blank system, one without pihole already installed

## WARNING
DO NOT USE ON PRODUCTION SYSTEM UNLESS YOU KNOW WHAT YOUR DOING

## Install
* Update hosts file and change IP to your host
* Update vars/vars.yml with the password you want for pihole GUI
* Run ansible-playbook -i hosts tasks/main.yml

## Change Log 
10/29/2023 - Initial Creation  

## Sometimes the lie is easier to live with ~ Tom

