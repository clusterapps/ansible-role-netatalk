clusterapps.netatalk
=========

Deploy Apple Time Machine target on EL8

Requirements
------------

The focus on the role is TimeMiachine. To prepare the machine, run the clusterapps.rhbase role first.

Role Variables
--------------

afp_tmgroup: POSIX group

afp_tmpath: /path/to/directory

Dependencies
------------

Not required, but helps:
- clusterapps.rhbase

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: fileservices
      roles:
         - { role: clusterapps.netatalk, afp_tmgroup: users }

License
-------

BSD

Author Information
------------------

Michael Cleary <michael@cleary.me>
