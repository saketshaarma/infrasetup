Role Name
=========

This role installs base packages required on all hosts like, git, ntp, setting up MOTD, Login Banner, setting up systcl.conf file parameters.

Role Variables
--------------
This role installs git through source, so need to update the version of the git you want to isntall along with its download location inside vars/main.yml


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - base

