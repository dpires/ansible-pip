[![Build Status](https://travis-ci.org/dpires/ansible-pip.svg?branch=master)](https://travis-ci.org/dpires/ansible-pip)

Role Name
=========

An Ansible role to install pip.

Requirements
------------

N/A

Role Variables
--------------

 - `pip_pip_exe` The pip executable, defaults to `pip`
 - `pip_python_exe` The python executable, defaults to `python`
 - `pip_temp_install_dir` The directory where to download the pip installer, defaults to `/tmp`
 - `pip_install_file` The pip installer, defaults to `get-pip.py`
 - `pip_installer_url` The pip installer url, defaults to `http://bootstrap.pypa.io/{{ pip_install_file}}`

Dependencies
------------

N/A

Example Playbook
----------------

```
    - hosts: all
      roles:
         - { role: dpires.pip }
```

License
-------

MIT

Author Information
------------------

David Pires
