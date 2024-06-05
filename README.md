# DBA Scripts
Repository of diverse day-to-day scripts for a DBA.

Scripts developed for daily routines, automation projects with Ansible and shell scripting. Content constantly developing and evolving.

:warning:

:point_right:


### Connect to Local Postgres Server
If you are running psql and Postgres server on the same machine, just launch psql:
```bash
psql -U <username> <dbname>
```

And type `:dba <Enter>` in psql. (Or `\i /path/to/postgres_dba/start.psql` if you haven't added shortcut to your `~/.psqlrc` file).

– it will open interactive menu.
