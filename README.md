# PowerPi 

An Ansible playbook for deploying a fleet of Raspberry Pi's for APC UPS power monitoring

```shell
$ # Setup your shell environment if you haven't done so already
$ eval `ssh-agent -s`
$ ssh-add id_rsa

$ # Deploy
$ ansible-playbook -i hosts.ini deploy.yml
```

### License 

This project is licensed under the MIT license.
