Ansible-Role-Composer
===================

Role to install composer and dependencies in Debian and RPMs.

Currently Role Supports Laravel Installer along with composer.

PreRequests
-----------
- Composer Requires Latest version of PHP > 7.0

Role Variables
--------------
```
# Specify user for composer //should not be root.
composer_user: admin

### If true it will Install Laravel for composer_user
Install_Laravel: true
```


Example Playbook
----------------

    - hosts: YOUR-HOST-OR-GROUP
      roles:
    	- Ansible-Role-Composer

License
-------

MIT

Author - Rahul Sharma
------------------

[Github](https://github.com/Rahulsharma0810)

[Facebook](https://www.facebook.com/rahulsharma0810)