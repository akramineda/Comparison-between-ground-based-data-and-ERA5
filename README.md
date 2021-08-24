# Comparison between Ground-based Synoptic Data and ERA5 Reanalysis Data in Iran

With the spirit of reproducible research, this repository contains codes required to produce the results in the manuscript:

> N. Akrami, K. Ziarati, and S. Dev, Comparison between Ground-based Synoptic Data and ERA5 Reanalysis Data in Iran, *Proc. Progress In Electromagnetics Research Symposium (PIERS)*, 2021.

## Code Organization
All codes are written in `python3`.

### Dependencies
The following libraries should be installed before the execution of the codes.

- Xarray: `pip install xarray`
- numpy: `pip install numpy`
- pandas: `pip install pandas`
- matplotlib: `pip install matplotlib`
- scikit-image 0.17.2: `pip install scikit-image`


### Data
Two data sets are used in this work. We are releasing the processed data that we used in this work. You may find the processed data in data folder in repository.
- One is [ERA5 Reanalysis Data](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels?tab=form) from ECMWF. 
- Other is the ground-based meteorological data collected from 5 synoptic stations from the [Iran Meteorological Organization](https://www.irimo.ir).


### Scripts
- `Compare_ERA5_Synoptic.ipynb`: Run this script to extract data (ERA5 and ground-based) and obtain the plots and other results of the manuscript. 
