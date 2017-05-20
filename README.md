n2n
=========

Ansible role for installing and configuring Ntop's n2n

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: kostyrev.n2n
      vars:
        n2n_install_from_tar_gz: yes
        n2n_base_download_url: http://mirror.example.com
        n2n_community: 'community'
        n2n_accept_multicast: True
```

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
