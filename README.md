postgresql-backup
=========

Set up local postgres backups.

Requirements
------------

None.

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`postgresql_backup_user` | restic | Group which owns the postgresql backup

Dependencies
------------

None.

Example Playbook
----------------

    - servers: db
      role:
        - postgresql-backup

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
