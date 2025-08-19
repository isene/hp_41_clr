# My basic clear routine for the HP-41 calculator

[![HP-41](https://img.shields.io/badge/HP--41-Calculator-orange)](https://en.wikipedia.org/wiki/HP-41C)
[![License](https://img.shields.io/badge/License-Public%20Domain-brightgreen.svg)](https://unlicense.org/)
[![GitHub stars](https://img.shields.io/github/stars/isene/hp_41_clr.svg)](https://github.com/isene/hp_41_clr/stargazers)
[![Stay Amazing](https://img.shields.io/badge/Stay-Amazing-blue.svg)](https://isene.org)

<img src="img/clr_logo.svg" align="left" width="150" height="150" alt="CLR Logo">
<br clear="left"/>
 
I assign this function ("CLR") to CLX and use this to clear the calculator.
 
It sets the flags to the RCLFLAG that is taken from the HEPAX file "C". To
initiate this file with the flags you have set, run "NEWC" first. If you later
change your flag setup (different FIX setting, DMY, etc), simply run NEWC
again to update the HEPAX file "C" to your new settings.

After clearing the stack and Alpha and resetting the calculator to the flag
settings stored in the HEPAX file "C", the program stops.

Upon pressing R/S, the program commences to show the current week number
and the illuminated fraction of the Moon's disk (with a "+" appended if the
Moon phase is growing or a "-" if the phase is shrinking).

Pressing R/S again yields the current Julian Day number.

Press R/S once more and the program displays the running clock.

Press R/S twice to clear the display, stack and Alpha and leave the calculator
in the program "CLR*" which marks the endpoint of the clear routine.
