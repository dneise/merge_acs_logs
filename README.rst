merge-acs-logs
===============

just a small tool to merge log files of ACS by timestamp

install with
------------

::

    pip install merge-acs-logs

Example Usage
-------------

.. code:: shell
   
   $ merge_acs_logs $ACSDATA/logs/*/*

It creates a file called ``merged_YYYY_MM_DDTHH_MM_SS.log`` in the CWD.


Help
-----

.. code:: shell
   
   $ merge_acs_logs --help 
    
for help
