## NOWCAST project
_disclaimer: I am not a software engineer so I apologize in advance for any atrocity you may find in this repository._ 😅


This is the index repo for all the other repositories for this proyect.

## Repositories in the proyect
Here is a list with the links of all the repositories needed for this proyect

  * [correlation module](https://github.com/tomasrojasc/correlation-module-nowcast): is the repository in charge of computing the cross correlations between time series.
  * [wind module](https://github.com/tomasrojasc/wind-module-nowcast): This repository manages all the wind data of interest for the project by the [ECMWF](https://www.ecmwf.int/)
  * [time series module](https://github.com/tomasrojasc/time-series-module-nowcast): This module takes the csv files for the sites to inspect, and return a binary file for the latter viewing of the data.
  * [GUI module](https://github.com/tomasrojasc/gui-module-nowcast): This module takes all the data above and makes a GUI with [Bokeh](https://docs.bokeh.org/en/latest/index.html#)
  * [PDF Module](https://github.com/tomasrojasc/PDF-module-nowcast): This module makes pdf for looking determined years by eye and see if there is somenthing interesting
## Important considerations
For all the computations done in this modules, site1 and site2 should be consistent, and if a cross correlation has positive time, it means that site1 was before site2, the opposite is true if the correlation time is negative. The same principle applies with the predicted times in the wind module.

For formatting the MASS data, there is a Jupyter Notebook Fuyan has. NOTE: I am founding errors in that part so I have to review it, in the meanwhile you can ask me the corrects files for that vie email.

## Credits
  * The pydcf bby Damien Robertson used in the correlation module can be found [here](https://github.com/astronomerdamo/pydcf).

## Thaks
I want to thank ESO and in particular to my supervisor Fuyan Bian.
