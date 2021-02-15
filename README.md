# Pen-Based Recognition of Handwritten Digits
## Introduction

### Description

A digit database was created by collecting 250 samples from 44 writers. The samples written by 30 writers are used for training, cross-validation and writer dependent testing, and the digits written by the other 14 are used for writer independent testing. This database is also available in the UNIPEN format.

A WACOM PL-100V pressure sensitive tablet was used with an integrated LCD display and a cordless stylus. The input and display areas are located in the same place. Attached to the serial port of an Intel 486 based PC allowed to collect handwriting samples. The tablet sends $x$ and $y$ tablet coordinates and pressure level values of the pen at fixed time intervals (sampling rate) of 100 milliseconds.

So, the input vector size is 2*T, two times the number of points resampled. Spatial resampling to T=8,12,16 points was considered in the experiments and it was found that T=8 gave the best trade-off between accuracy and complexity.

### Features

16 continuous variables each between the range 0-100, two times the number of points resampled which are 8 that measure the x and y coordinates and pressure values which are measured by the device which then reports these values to the computer.

### Target Variable

The Target Variable is a categorical variable which are digits between 0-9 that represent 10 classes/categories. Hence it is a classification Task and not a regression one.
