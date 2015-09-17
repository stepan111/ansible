## Ansible playbooks

Here will be some playbooks for installing some stuff on Slackware and securing it.

## Usage

I use ["Vagrant"](https://docs.vagrantup.com/v2/why-vagrant/index.html) for fast vm creation. Just run:

```
# vagrant up

```
 And:

```
# vagrant  provision
```



## Playbook description

At first time here will be created few ansible roles. Here they are:

- common - common firewall and access policyies for server.
- mysql - Mysql installation and configuration.
- backup - role for backing up server common configuration
- backup_mysql - databases backup role.
