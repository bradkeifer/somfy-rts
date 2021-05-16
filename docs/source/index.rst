.. somfy-rts documentation master file, created by
   sphinx-quickstart on Tue May 11 15:15:12 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. toctree
   :maxdepth: 2
   :caption: Contents:


somfy_rts Documentation
=======================

Introduction
------------
The somfy_rts package has been developed to provide an API for communication
with the Somfy RS485 RTS Transmitter(s) to control devices such as blinds,
shutters, awnings or lights. Multiple transmitters may be
connected on a single RS485 multi-drop network.

Connectivity is either via a TCP socket or a serial port.

API Reference
-------------

.. autoclass:: somfy_rts.RTSProtocol
   :members:

Developer documentation
-----------------------
The package has currently only been tested and used for the control of blinds
using a socket connection. Feel free to test it for other configurations and
provide feedback to the author. Bugs can be reported 
`here <https://github.com/bradkeifer/somfy-rts/issues>`_.

To obtain the full code, you can clone the git repository:

.. code-block:: bash

   git clone https://github.com/bradkeifer/somfy-rts

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

