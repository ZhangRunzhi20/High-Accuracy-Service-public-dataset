# High-Accuracy-Service-public-dataset
HAS data collected by receivers Septentrio AsteRx-m3 Pro+, NovAtel OEM729, and China SINO K803
In this repository, files ending with .HAS are corresponding binary files cached by the receiver.

A C/C++ HAS decoder, named HASPPP, is currently being organized and open-sourced.
The results of HAS time comparison using RTKLIB embedded with the HASPPP are stored in the ./SINO/time comparison folder.
The files in this folder with the extension .trace contain the local receiver clock offsets (GPS, GLONASS, Galileo, BDS) calculated by the RTKLIB.
The files with the extension .t contain the results of time comparison, while the files with the extension .x represent the time comparison results errors with respect to IGS final clock products.

