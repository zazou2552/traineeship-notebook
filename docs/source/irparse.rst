irparse
=======
|
irparse coverts the downloaded data to files which can be imported into the database

        irparse --all 1>/data/irdata18/logs/irparse.log 2>&1 &

The data flow is shown below:

.. figure:: images/unpack.png
    :width: 700px
    :align: center
    :height: 50px
    :alt: alternate text
    :figclass: align-center

    unpacked data

| 


.. figure:: images/irparse.png
    :width: 1000px
    :align: center
    :height: 50px
    :alt: alternate text
    :figclass: align-center

    irparse output

| 

.. figure:: images/importparse.png
    :width: 500px
    :align: center
    :height: 100px
    :alt: alternate text
    :figclass: align-center

    irimport imports parsed data



| 
Next step:

:doc:`irimport`
