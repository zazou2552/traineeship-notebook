irprevious
==========
| 
This command is executed on the previous build database. This script extracts the previously constructed rog's and rig's so they can later be imported into the newly build version:: 

	irprevious --pgsql irdata17 1>/data/irdata17/logs/previous.log 2>/data/irdata17/logs/previous.error.log & 
| 
The output of this script are 4 files:

|  
| --rig2rigid
| --rog2rogid
| --sequence_archived
| --sequence_archived_original


| :

These files are moved from server to server by using scp::
	scp /data/irdata17/sequences_archived_original  tom@psicquic-1804-2021:~/sequences_archived_original

| 
Next step:

:doc:`irbuild`

