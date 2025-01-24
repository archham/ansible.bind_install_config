# Install & configure Bind DNS Server with Ansible

## Info
Ansible project to create and configure new Bind DNS slave server on Rocky Linux.

## Prerequisites
* Rocky Linux
* Ansible Evironment

## How to

Add your named.conf to the etc dir and correct the playbook.yaml file accordingly

── etc
    ├── logrotade.d
    │   ├── dnstap
    │   └── named
    └── named.conf


