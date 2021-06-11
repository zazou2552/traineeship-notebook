irimport
========
| 
irimport imports all of the parsed data into the database. This process can be executed on seperate databases or all at once. 
This step can take a long time because of the multiple large sql querys::
	
	irimport --all 1>/dataext/irdata18/logs/import.log 2>/dataext/irdata18/logs/import.errors &
| 
Next step:
:doc:`irprevious`

