mt4R
========

This is MT4 -> R interface library, originally developed by Bernd Kreuss and distributed [here](https://sites.google.com/site/prof7bit/r-for-metatrader-4).
CHANGES
----------

See [CHANGES.md](https://github.com/micclly/mt4R/blob/new_mql4_support/CHANGES.md)

SAMPLES
----------

### MQL4/Scripts/mt4RTest.mq4

A simple script to test mt4R working correctly.

#### Requires

* MT4 build 600 or later
* R executable
* MQL4/Include/mt4R.mqh

#### Installation

1. Copy MQL4/Include/mt4R.mqh to ``<TERMINAL_DATA_PATH>/MQL4/Include/```
1. Copy MQL4/Scripts/mt4Rtest.mq4 to ``<TERMINAL_DATA_PATH>/MQL4/Scripts/``
1. Change ``R_command`` to your installation path 
1. Run mt4RTest script from MT4 


### MQL4/Experts/arbomat.mq4 and MQL4/Experts/trendomat.mq4

Expert advisors, originally distributed [here](https://sites.google.com/site/prof7bit/r-for-metatrader-4/trend-o-mat-arb-o-mat).

This distribution contains modified version of common_functions.mqh and experts to adapt to new MQL4.

#### Requires

* MT4 build 600 or later
* R executable
* MQL4/Include/mt4R.mqh
* MQL4/Include/common_functions.mqh

#### Installation

1. Copy MQL4/Include/mt4R.mqh to ``<TERMINAL_DATA_PATH>/MQL4/Include/```
1. Copy MQL4/Include/common_functions.mqh to ``<TERMINAL_DATA_PATH>/MQL4/Include/```
1. Copy MQL4/Experts/arbomat.mq4 to ``<TERMINAL_DATA_PATH>/MQL4/Experts/``
1. Copy MQL4/Experts/trendomat.mq4 to ``<TERMINAL_DATA_PATH>/MQL4/Experts/``
1. Change ``RPATH`` to your installation path 
1. Run experts from MT4
1. If you successfully installed experts, you'll soon (maybe 30 seconds or so few minutes)
   see the Arb-O-Mat or Trend-O-Mat graph generated by R.
