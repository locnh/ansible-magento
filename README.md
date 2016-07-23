## Supported tags and respective `Playbook` links
#### Production
* [`CentOS 6` (*centos-6.yml*)](https://github.com/locnh/ansible-magento/blob/master/centos-6.yml)

#### Sandbox
* [`CentOS 6` (*centos-6.yml*)](https://github.com/locnh/ansible-magento/blob/develop/centos-6.yml)

## What is this ?
Ansible playbook for setting up environment for Magento, it will install server with NginX / Apache and PHP with compatible version and modules for Magento.

Sandbox build for `Magento 2` comes with composer, nodejs, grunt.

![Magento Logo](https://upload.wikimedia.org/wikipedia/en/c/c2/Magento_logo.png)

## How to start
Run playbook and tell it what you need, for example the node is running `CentOS 6`:
  ```
  $ ansible-playbook centos-6.yml
  ```

## TODO
- [x] CentOS 6
- [ ] CentOS 7
- [ ] Ubuntu LTS 14.04
- [ ] Ubuntu LTS 16.04

## Contribute
1. Fork me
2. Make changes
3. Create pull request
4. Grab a cup of coffee
