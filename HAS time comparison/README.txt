An open-source C/C++ Galileo High Accuracy Service (HAS) decoder package HASPPP will be released.
Here are the data and results of the time transfer experiment conducted by RTKLIB 
embedded with HASPPP using HAS data cached by China SINO.

Preparation:
Observation and navigation ephemeris files can be obtained from the IGS data center.
The HAS binary data for the days of year 166 to 179 in 2023 cached by the SINO receiver is utilized, 
and the files can be obtained in the ../SINO folder.

Results:
The folder result contains result files of Precise Point Positioning (PPP) time transfer. Files ending with .trace represent receiver clock offset
(GPS, GLONASS, Galileo, and BDS) calculated through RTKLIB embedded with HASPPP using the HAS product.
Files ending with .t represent time comparison link results, while .x denotes error sequences of HAS time comparison
results with respect to the IGS final clock offset product.