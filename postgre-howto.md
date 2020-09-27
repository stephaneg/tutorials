# accounts and environment
postre user : postgres
distrib installation : /usr/lib/psotgresql/12/bin


# starting the database server
postgres -D /usr/local/pgsql/data

starting in the background :
postgres -D /usr/local/pgsql/data >logfile 2>&1 &

with the pg_ctl wrapper :
pg_ctl start -l logfile
