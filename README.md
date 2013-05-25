librec
======

This is a fake public library database for demonstrating various SQL and PostgreSQL concepts.  It's currently incomplete but already has useful data.  It corresponds to no known library software.  PostgreSQL Experts Inc. uses this database for teaching SQL, and it's provided here to help people using PostgreSQL.

Book data was harvested off the internet on publically available publisher's catalogs, and then munged in order to provide further variety in the data.  We believe that this is in accord with rights to the data; if that's incorrect, publishers are encouraged to contact us and the data will be deleted.

More information regarding using the sample database will go in the docs here when I have time.

Loading The Librec
------------------

As "postgres" on your local machine:

   createdb librec
   pg_restore -d librec -v librec.dump

Or, if you use pgAdmin3, you can use its backup restorer to create the database from librec.dump