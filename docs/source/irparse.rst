irparse
=======
|
irparse coverts the downloaded data to files which can be imported into the database::

        irparse --all 1>/data/irdata18/logs/irparse.log 2>&1 &

| 
The data flow is shown below:



.. figure:: images/unpack.png
    :width: 350px
    :align: center
    :height: 25px
    :alt: alternate text
    :figclass: align-center

    unpacked data

| 


.. figure:: images/irparse.png
    :width: 500px
    :align: center
    :height: 25px
    :alt: alternate text
    :figclass: align-center

    irparse output

| 

.. figure:: images/importparse.png
    :width: 300px
    :align: center
    :height: 75px
    :alt: alternate text
    :figclass: align-center

    irimport imports parsed data



| 
Next step:

:doc:`irimport`
