Setup
=====

Rails
-----
rails new myapp -T --database=postgresql


dwu@dwu:~/Programming/fatpanda (master)$ psql -U $USER
psql (9.3.2)
Type "help" for help.

dwu=# CREATE ROLE fatpanda;
CREATE ROLE
dwu=# ALTER ROLE fatpanda LOGIN;
ALTER ROLE
dwu=# ALTER ROLE fatpanda CREATEDB;
ALTER ROLE
