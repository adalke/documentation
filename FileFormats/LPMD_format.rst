.. _LPMD_format:

LPMD format (lpmd)
==================

**Read and write LPMD's atomic configuration file**




Read Options
~~~~~~~~~~~~ 

-s  *Output single bonds only*
-b  *Disable bonding entirely*


Write Options
~~~~~~~~~~~~~ 

-f <num>  *Indicate the level of the output file: 0 (default), 1 or 2.*
-m <num>  *Indicate the mode for level 2 output files*

        0 (default) is for accelerations and 1 for forces
-c <vectorcells>  *Set the cell vectors if not present*

        Example: ``-xc 10.0,0,0,0.0,10.0,0.0,0.0,0.0,20.0``
-e  *Add the charge to the output file*


