## Supported tags and respective `Playbook` links
#### Production
* [`CentOS` (*centos.yml*)](https://github.com/locnh/ansible-magento/blob/master/centos.yml)

#### Sandbox
* [`CentOS` (*centos.yml*)](https://github.com/locnh/ansible-magento/blob/develop/centos.yml)

## What is this ?
Ansible playbook for setting up environment for Magento, it will install server with NginX / Apache and PHP with compatible version and modules for Magento.

Sandbox build for `Magento 2` comes with composer, nodejs, grunt.

![Magento Logo](http://www.elevateweb.co.uk/wp-content/themes/porto/assets/img/headers/mage-logo.png)

## How to start
Run playbook and tell it what you need, for example the node is running `CentOS 6`:
  ```
  $ ansible-playbook centos.yml
  ```

## TODO
- [x] CentOS 6
- [x] CentOS 7
- [ ] Ubuntu LTS 14.04
- [ ] Ubuntu LTS 16.04

## Contribute
1. Fork me
2. Make changes
3. Create pull request
4. Grab a cup of coffee
