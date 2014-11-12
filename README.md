rkhunter
=========

Install and manage a [rkhunter](http://rkhunter.sourceforge.net) installation.

Requirements
------------

No external dependencies.

Role Variables
--------------

The following variables can be overridden by inventory:

- **rkhunter_mail**: Recipient of *rkhunter* reports.  Default is *root@localhost*.
- **rkhunter_diag_scan**: When running reports, whether to do full
  diagnostic scan.  Default is *no*.
- **rkhunter_ssh_prot_v1**: Whether SSH V1 is enabled.  Legal values: 0,
  1, 2.  Default is *2*.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: sfromm.rkhunter }

License
-------

GPLv2

Author Information
------------------

See https://github.com/sfromm
