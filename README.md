# masters_thesis

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/panmits86/masters_thesis/master)



## Satellite Altimetry Data

Download data of Jason 3 and SARAL-AltiKa satellite altimeters from the Aviso Online Data Extraction Service.

Link: http://odes.altimetry.cnes.fr/#7zzzzzzzzzzz:3

### Data Availability:
Jason 3 Data is available from 12/2/2016. SARAL/AltiKa data is available from 2013 and the drifting phase begun in 5/7/2016.

Along-tracks of Jason 3 for the domain of interest are 126 & 243 for the IGDR products. Data from the 050 & 167 passes will be added as well.

### Data downloaded:
SARAL/AltiKa Level 2 IGDR data for 7/2016 until 01/01/2020, JASON 3 Level 2 IGDR data for 2016 until 01/01/2020.


  
## Buoys

The Domain of Interest is the Southern New England coast. 
The coordinates are: 40°-42°N in latitude and 74°-70°W in longitude (or 286°-290°).
The list of buoys with available wind and wave height data is included in the buoys.xlsx file.
Data can be downloaded from the National Data Buoy Center.
Link: https://www.ndbc.noaa.gov/


## Notebooks

1. Map of the domain including the buoys.
2. Map of the satellite tracks in the domain.
3. Organize the data to pandas and merge the into single .txt files for wind and wave parameters for each buoy.
