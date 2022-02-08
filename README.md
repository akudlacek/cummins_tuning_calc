# cummins_tuning_calc
Various tuning calculators for 5.9 Cummins  
  
Most tables have password protection to protect against accidental modification.  
The password is 1234  
  
Some of these calculators require the XonGrid add-in to perform interpolation. You will  
need this add-in which can be found here: http://xongrid.sourceforge.net/  
  
**NOTE**  
~~I found that XonGrid does not work with 64bit Office 365 even you install the 64bit  
version. To use this add-in you will need 32bit Office 365 and to install the 32bit  
version of XonGrid.~~

xongrid version 3 seems to work.
  
5.9 Cummins Tune Calc (all stock loaded) protected  
INPUT TABLES (GREEN):  
Main Inj Duration  
Pilot Qty  
Post Qty  
Main Timing  
Pilot Timing  
Post Timing  
Fuel Pressure  
Limiters  
Pilot Inj Pulse (found way on right side)  
Post Inj Pulse  (found way on right side)  
  
OUTPUT TABLES (RED):  
End of Main Deg Calc  
Main Inj Norm RPM Calc  
Post Duration Calc  
Pilot Duration Calc  
Pilot to Main Calc  
Main to Post Calc  
End of Pilot Deg Calc  
End of Post Deg Calc  

CALCULATORS (ORANGE):  
Main Time Calc (Calculates main timing based off of min end of main injection degrees)  
Pilot Timing Calc (Calculates pilot timing based off of desired pilot to main delay or max degrees start)  
Post Timing Calc (Calculates post timing based off of desired end of post degrees)  
  
GRAPH (BLUE):  
Timing Chart Mod (Graph of injection events for all given input tables)  
Timing Chart Stock (Graph of injection events for all given stock tables, this always shows stock)  
