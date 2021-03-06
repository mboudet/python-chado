analysis
========

This section is auto-generated from the help text for the chakin command
``analysis``.


``add_analysis`` command
------------------------

**Usage**::

    chakin analysis add_analysis [OPTIONS] NAME PROGRAM PROGRAMVERSION

**Help**

Create an analysis


**Output**


    Analysis information
    
**Options**::


      --algorithm TEXT      analysis algorithm
      --sourceversion TEXT  analysis sourceversion
      --sourceuri TEXT      analysis sourceuri
      --description TEXT    analysis description
      --date_executed TEXT  analysis date_executed (yyyy-mm-dd)
      -h, --help            Show this message and exit.
    

``delete_analyses`` command
---------------------------

**Usage**::

    chakin analysis delete_analyses [OPTIONS]

**Help**

Delete analysis


**Output**


    None
    
**Options**::


      --analysis_id INTEGER  analysis_id filter
      --name TEXT            analysis name filter
      --program TEXT         analysis program filter
      --programversion TEXT  analysis programversion filter
      --algorithm TEXT       analysis algorithm filter
      --sourcename TEXT      analysis sourcename filter
      --sourceversion TEXT   analysis sourceversion filter
      --sourceuri TEXT       analysis sourceuri filter
      --description TEXT     analysis description
      -h, --help             Show this message and exit.
    

``get_analyses`` command
------------------------

**Usage**::

    chakin analysis get_analyses [OPTIONS]

**Help**

Get all or some analyses


**Output**


    Analysis information
    
**Options**::


      --analysis_id INTEGER  analysis_id filter
      --name TEXT            analysis name filter
      --program TEXT         analysis program filter
      --programversion TEXT  analysis programversion filter
      --algorithm TEXT       analysis algorithm filter
      --sourcename TEXT      analysis sourcename filter
      --sourceversion TEXT   analysis sourceversion filter
      --sourceuri TEXT       analysis sourceuri filter
      --description TEXT     analysis description
      -h, --help             Show this message and exit.
    
