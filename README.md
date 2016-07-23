## Supported tags and respective `Playbook` links
### Production build
* [`CentOS 6` (*centos-6.yml*)](https://github.com/locnh/ansible-magento/blob/master/centos-6.yml)

### Sandbox build
* [`CentOS 6` (*centos-6.yml*)](https://github.com/locnh/ansible-magento/blob/develop/centos-6.yml)

## What is this ?
Ansible playbook for setting up environment for Magento, it will install server with NginX / Apache and PHP with compatible version and modules for Magento.

Sandbox build for Magento 2.x (`2-dev`) comes with composer, nodejs, grunt.

![Magento Logo](https://upload.wikimedia.org/wikipedia/en/c/c2/Magento_logo.png)

## How to start
Run playbook and tell it what you need, for example the node is running `CentOS 6`:
  ```
  $ ansible-playbook centos-6.yml
  ```

## Contribute
1. Fork me
2. Make changes
3. Create pull request
4. Grab a cup of coffee
