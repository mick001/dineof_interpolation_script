# DINEOF interpolating R script
A script for interpolating netCDF files using DINEOF.

The main parts of this work are:

1. main_dineof.R is the main script executing the loading, interpolation and saving procedures of satellite netCDF images.
2. checklist_exec.R is the checklist to follow in order to execute the script correctly.
3. main_dineof_LARGE_DATA.R is a version of the main script which uses a SQLite database and therefore can manage more data. 

## Dependencies
Dependencies can be found in the file dependencies.txt. Please make sure to install all the requested dependencies before running the script.

Since *sinkr* package (which provides the dineof interpolating function) is not available on CRAN, a copy of it has been stored in this repository to ensure its future availability in its state at the time of development.

## Execution checklist
The execution checklist and instructions can be found in the file checklist_exec.R.
