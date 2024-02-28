![Testing](https://github.com/albertodescalzo/ansible-role-kirgenotyping/workflows/Role-Testing/badge.svg)


Kirgenotyping
=========

Bioninformatic tools to be installed in any Linux VM in order to run the following Killer-cell immunoglobulin-like receptors KIR inference pipeline: https://github.com/albertodescalzo/KIRgenotyping/. For more information about the pipeline, see the GitHub page.

Requirements
------------

Role and inference pipeline were used within the de.NBI Cloud (German Network for Bioinformatics Infrastructure) in a VM with Ubuntu 20.04 and 22.04, but it should work in other cloud suppliers. 

Role Variables
--------------

Adapt the software versions to your preferences. The given variables were used to run the pipeline. Additionally, pay attention to `home_path` and `username`. They should be set up to `/home/runner/work`and `runner` when testing CI.   

Dependencies
------------



Example Playbook
----------------

  - hosts: denbi_vms
  roles:
    - kirgenotyping

License
-------

BSD

Author Information
------------------

Email: Alberto.Descalzo.Garcia@hhu.de
