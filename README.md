Mailing List Stats
==================

Description
-----------
Mailing List Stats is a command line based tool used to analyze
mboxes. It downloads the mboxes in a directory where database
will be created. It stores all the information which is contained
in a e-mail.


License
-------

Licensed under GNU General Public License (GPL), version 2 or later.


Download
--------

Releases:

  * https://github.com/MetricsGrimoire/MailingListStats/downloads

Latest version:

    $ git clone git://github.com/MetricsGrimoire/MailingListStats.git


Requirements
-------------
`mlstats` needs the following dependencies (either MySQL or PostgresQL):

  * MySQL:
    * python-mysqldb
    * mysql-server
  * Postgresql:
    * psycopg2
    * postgresql-server (it has been tested with 8.4 and 9.1)


Installation
------------
You can install MLStats running setup.py script:

    # python setup.py install

If you don't have root privileges, use the `--prefix` option to indicate 
the directory where `mlstats` will be installed. For more details, take a 
look at the help of the installer:

    $ python setup.py install --help

You are ready to use `mlstats`.


Running mlstats
---------------

More options, and a more detailed info about the options, can be
learnt by running `mlstats --help`

The backend postgres requires the database already exists. The creation
of tables must be done manually. There is a SQL script with the schema
in `db/data_model_pg.sql` that can be used for this purpose.


Analysis
--------

[To be written]


Improving MailingListStats
---------------------------

Source code, wiki and it is available on [Github].

  [GitHub]: https://github.com/MetricsGrimoire/MailingListStats

Please write to the developers mailing at
libresoft-tools-devel@lists.morfeo-project.org

If you want to receive updates about new versions, and keep in touch
with the development team, consider subscribing to the [mailing list][1].
It is a very low traffic list (< 1 msg a day):

  [1]: https://lists.morfeo-project.org/mailman/listinfo/libresoft-tools-devel


Credits
-------

`mlstats` has been originally developed by the GSyC/LibreSoft group at
the Universidad Rey Juan Carlos in Mostoles, near Madrid (Spain). It is
part of a wider research on libre software engineering, aimed to gain
knowledge on how libre software is developed and maintained.
 

Main authors
------------

  * [Israel Herraiz]               <isra at herraiz org>
  * Jorge Gascon Perez             <jgascon at gsyc.escet.urjc.es>


Contributors
------------

  * [Dave Neary]                   <dneary at maemo org>
  * [Germán Poo-Caamaño]           <gpoo at gnome org>
  * [Luis Cañas]                   <lcanas at bitergia com>

  [Israel Herraiz]: http://herraiz.org/
  [Dave Neary]: http://blogs.gnome.org/bolsh/
  [Germán Poo-Caamaño]: http://calcifer.org/
  [Luis Cañas]: http://sanacl.wordpress.com/
