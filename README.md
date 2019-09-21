Cloud Growpart
=========

Installs the cloud-init-utils and expands the root partition.

Requirements
------------

None

Role Variables
--------------

```yaml
root_device: /dev/sda
```

This specifies the device to expand a partition on.

```yaml
root_partition: 2
```

This specifies which partition on the device to expand.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: chrisbalmer.cloud-growpart }

License
-------

MIT

Author Information
------------------

Chris Balmer
