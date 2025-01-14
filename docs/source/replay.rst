.. _replay:

Replay
======

1. install python package ``flask``

.. code-block:: shell

    pip install flask

2. enter the ``frontend`` folder and download required libraries

.. code-block:: shell

    python init.py

3. start the frontend server by

.. code-block:: shell

    python app.py

the frontend will be running on port 8080 of localhost

4. put ``roadnet.json`` and ``replay.txt`` generated by CityFlow into ``frontend/replay`` folder

.. note::

    Sample replay files can be downloaded by running ``download_replay.py``.

5. checkout the replay in the browser with following url

.. code-block:: shell

    http://localhost:8080/?roadnetFile=roadnet.json&logFile=replay.txt
