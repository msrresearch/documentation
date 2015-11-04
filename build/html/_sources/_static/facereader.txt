facereader_client
*****************

Code documentation
==================

.. currentmodule:: facereader
.. autoclass:: FaceReader
	:members:


Logs
====

At the moment FaceReader supports to kinds of logs: the detailed and 
the state log. While the first mentioned includes all data gathered 
while analyzing a frame, the later log only contains the at the moment 
dominant facial expression.

Detailed log
------------

Detailed logging can be enabled by calling the function 
:py:func:`start_detailed_log` and can be stopped by calling 
:py:func:`stop_detailed_log`.

State log
---------

State logging can be enabled by calling the function 
:py:func:`start_state_log` and can be stopped by calling 
:py:func:`stop_state_log`.
