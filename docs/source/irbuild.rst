irbuild
=======
| 
The final step is to join all the data together and assign all the proteins and interactions with there rogid and rigid.
This is done with the irbuild command::

	irbuild --build --reports --output 1>>/data/irdata18/logs/build.log 2>>/data/irdata18/logs/build.error.log &
| 
| --build: building the database in psql
| 
| --reports: making statistics and tables of the final build
| 
| --output: exporting a tabular format of the database

