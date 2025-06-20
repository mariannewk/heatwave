# Marine Heatwaves detection code

# Usage

To detect marine heatwaves in the Barents Sea using Copernicus marine data run the file heatwaves_barents.ipynb in a Jupyter Notebook. 

Originally authored by Vidar Lien using the marineHeatWaves package (see below), this Python code has been adapted into a Jupyter Notebook by Marianne Williams-Kerslake. When running the Jupyter Notebook in EDITO the marineHeatWaves package is already installed. 

# Marine Heatwaves package

marineHeatWaves is a module for python which implements the Marine Heatwave (MHW) definition of Hobday et al. (2016). A version written in R is also [available](https://robwschlegel.github.io/heatwaveR/index.html).

# Contents

|File                 |Description|
|---------------------|-----------|
|CHANGES.txt          |A list of software versions and changes|
|docs/                |Documentation folder|
|LICENSE.txt          |Software license information|
|marineHeatWaves.py   |marineHeatWaves module|
|README.md            |This file|
|setup.py             |Installation script (see below)|

# Installation

This module can be installed one of two ways:

1. Standard python install. On Linux/UNIX or OS X run the following command in the terminal:  
  ```
  python setup.py install
  ```  
  or on windows run this at the command prompt (not tested)  
  ```
  setup.py install
  ```
2. Alternatively just copy the marineHeatWaves.py to your working directory or any other directory from which Python can import modules.

Prequisite Python modules include numpy, scipy, and datetime.

# Documentation and Usage

Inside the documentation folder are the following helpful files and scripts:

|File                      |Description|
|--------------------------|-----------|
|marineHeatWaves_manual.htm|HTML file of IPython notebook outlining use of marineHeatWaves code to detect the "big three" historical marine heatwaves. Original data files (NOAA OI SST hi-res) not supplied due to copyright.|
|example_synthetic.ipynb   |IPython notebook outlining use of marineHeatWaves code to detect events from a synthetic time series. This notebook can be run by the user as it relies only on internally-generated synthetic temperature data.|
|example_synthetic.html    |Static HTML version of example_synthetic.ipynb.|
|mhw_stats.py              |Script with some examples of how to output plots, stats, and data files from marineHeatWaves detection code. Requires a subfolder to be created with the name 'mhw_stats', to which all files are output.|

# References

Hobday, A.J. et al. (2016), A hierarchical approach to defining marine heatwaves, Progress in Oceanography, 141, pp. 227-238, doi: 10.1016/j.pocean.2015.12.014 [pdf](http://passage.phys.ocean.dal.ca/~olivere/docs/Hobdayetal_2016_PO_HierarchMHWDefn.pdf)

# Contact

marianne.williams-kerslake@nersc.no  
 
