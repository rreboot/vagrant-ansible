# vagrant-ansible
vagrant + ansible personal boilerplate

## Action list
* Add key, repo and install Nodejs 7.x
* Copy .bashrc in VM

**Issue**: Installation Nodejs only the following distributions:
- jessie                                
- lucid
- precise
- saucy  
- sid   
- trusty
- utopic
- vivid
- wheezy
- wily
- xenial

For install on non-Ubuntu target (Mint, Debian) change `{{ ansible_distribution_release }}` in playbook.yml to required codename (e.g. xenial):

`repo: deb https://deb.nodesource.com/node_7.x xenial main`
