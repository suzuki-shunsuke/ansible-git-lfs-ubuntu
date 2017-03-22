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

Nothing.

Dependencies
------------

* [suzuki-shunsuke.git-ubuntu module](https://galaxy.ansible.com/suzuki-shunsuke/git-ubuntu/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.git-lfs-ubuntu
```

License
-------

MIT
