Ansible Role: libre-speedtest
=========

Ansible Role used to run a librespeed-cli on a remote machine.

Requirements
------------

The role does not require anything to run on RHEL and its derivatives.

Role Variables
--------------

Available variables are listed below, along with default values (see ```defaults/main.yml```):

``` yaml
base_url: "https://api.github.com/repos/librespeed/speedtest-cli/releases/latest"
```

Role variables can be stored with the hosts.yaml file, or in the main variables file.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mikepruett3.libre-speedtest }

License
-------

MIT

Author Information
------------------

Role created by [mikepruett3](https://github.com/mikepruett3) on [Github.com](https://github.com/mikepruett3/ansible-role-libre-speedtest).
