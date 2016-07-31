git-lfs-ubuntu
===============

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-git-lfs-ubuntu.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-git-lfs-ubuntu)

Install git-lfs on Ubuntu.

https://galaxy.ansible.com/suzuki-shunsuke/git-lfs-ubuntu/

Requirements
------------

Nothing.

Role Variables
--------------

* git_lfs_nonroot: Whether the remote_user is root or not. This variable is set automatically, and is used to execute tasks with the become option.

Dependencies
------------

* [suzuki-shunsuke.git-ubuntu module](https://galaxy.ansible.com/suzuki-shunsuke/git-ubuntu/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - { role: suzuki-shunsuke.git-lfs-ubuntu }
```

License
-------

MIT
