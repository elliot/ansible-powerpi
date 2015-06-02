# PowerPi 

An Ansible playbook for deploying a fleet of Raspberry Pi's for APC UPS power monitoring

It will install dependencies, download and configure the NRPE and create an in-memory overlay filesystem to prevent trashing your SD card.

### Usage

```shell
$ # Setup your shell environment if you haven't done so already
$ eval `ssh-agent -s`
$ ssh-add id_rsa

$ # Deploy
$ ansible-playbook -i hosts.ini deploy.yml
```

### License 

This project is licensed under the MIT license.
