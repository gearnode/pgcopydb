.. _pgcopydb:

pgcopydb
=========

pgcopydb - copy an entire Postgres database from source to target

Synopsis
--------

pgcopydb provides the following commands::

    pgcopydb
      copy-db  Copy an entire database from source to target
    + dump     Dump database objects from a Postgres instance
    + restore  Restore database objects into a Postgres instance
    + list     List database objects from a Postgres instance
      help     print help message
      version  print pgcopydb version

Description
-----------

The pgcopydb command implements a full migration of an entire Postgres
database from a source instance to a target instance. Both the Postgres
instances must be available for the entire duration of the command.

Help
----

To get the full recursive list of supported commands, use::

  pgcopydb help

Version
-------

To grab the version of pgcopydb that you're using, use::

   pgcopydb --version
   pgcopydb version
