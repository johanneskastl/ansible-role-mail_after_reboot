![Ansible Lint](https://github.com/johanneskastl/ansible-role-mail_after_reboot/workflows/Ansible%20Lint/badge.svg)

mail_after_reboot
=========

Create a systemd service that sends a mail after each reboot of the machine (aka during startup)

Requirements
------------

The machine must be able to send mails, i.e. it must have a working MTA like Postfix or some nullmailer etc.

Role Variables
--------------

None.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.mail_after_reboot'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
