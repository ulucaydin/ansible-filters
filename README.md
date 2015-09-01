# Ansible Filters
This is an open source library of Ansible filters which extends the functionality of Ansible.

## How to use it
Simply move the `filter_plugins` folder to the root directory of your Ansible project. To use it simply call the filter such as `"{{ my_var|filter_name }}"`.
For example: `"{{ google.com|dns_to_ip }}"`


For further assistance, please see the [official Ansible documentation](http://docs.ansible.com/ansible/developing_plugins.html#distributing-plugins).
