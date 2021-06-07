irinit
======

In the first step we will construct an empty database::

	createdb irdata18A

A directory for all the raw data and logs is made::


	mkdir /data/irdata18/logs


Irinit is then executed to fill the database with empty tables, the standard output is send to the logs directory::

	irinit --init 1>/data/irefindex18/logs/irinit.log 2>&1
	

next step:

:doc:`irdownload`


