## Ansible playbooks

Here will be some playbooks for installing teradek demo

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

- ssl - Generate self signed certificates.
- nginx - install and configure Nginx Proxy server
- python-web - install and configure sample python web service.
