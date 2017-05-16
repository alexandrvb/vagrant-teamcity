# Install teamcity server in Vagrant
## Requirements
* ansible >= 2.2
* Vagrant
## Running
```
vagrant up
vagrant ssh
ansible-playbook /vagrant/play.yml
```
## Access to teamcity
http://127.0.0.1:8111
