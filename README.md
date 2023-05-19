# Rohde and Schwarz ZVB20 QCodes
QCodes for the ZVB20 which are basically the QCodes pulled from the ZNB20 but slightly adjusted. Done with the help of Kyle Matkovic. Super jank but works. I've provided an example of using it in 'R&D ZVB20.ipynb'. So far I've only tested out the frequency sweeping and power sweeping. Code is pretty much pulled from the examples on the QCodes website.

## Changes to original rohde_schwarz folder
-Added a file Rohde_Schwarz_ZVB20.py 

-Added a file ZVB20.py

-Edited ZNB.py :

- Added max/min frequency (line 980)

- Added source power (line 393)

- Commented out the parameter "status" (line 482)

- Commented anything out that uses the parameter "status" (line 806, 913). The SCPI codes don't seem to work with the "status" parameter


