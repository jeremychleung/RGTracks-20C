<!-- # Reanalysis-Based Global Tropical Cyclone Tracks Dataset for the Twentieth Century (RGTracks-20C) -->
Reanalysis-Based Global Tropical Cyclone Tracks Dataset for the Twentieth Century (RGTracks-20C)
=====
[![DOI](https://zenodo.org/badge/698311843.svg)](https://zenodo.org/badge/latestdoi/698311843)<br />
This repository contains the Reanalysis-Based Global Tropical Cyclone Tracks Dataset for the Twentieth Century (RGTracks-20C).
<br /> <br />

**About the RGTracks-20C**
-----
- The RGTracks-20C is the first publicly available century-long reanalysis-based TC track dataset.
- The RGTracks-20C provides a long-term historical proxy record of global tropical cyclones spanning from 1850 to 2014, including their locations, timings, and intensities information.
- The current version of the dataset is constructed from the NOAA/CIRES/DOE 20th Century Reanalysis ([20CRv3](https://www.psl.noaa.gov/data/gridded/data.20thC_ReanV3.html)) based on two tropical cyclone tracking algorithms ([UZ](https://) and [OWZ](https://) trackers).
- Please refer to [Ye et al. (2023, under review)](https://) for more detail about the calculation procedure and the theory behind it.
 <br /> 
 
**Files**
-----
- Tropical cyclones extracted by the OWZ tracker
  - Location: [data/RGTracks-20Cv1_OWZ_1850-2014.csv](https://github.com/jeremychleung/RGTracks-20C/blob/main/data/RGTracks-20Cv1_OWZ_1850-2014.csv)
  - Temporal coverage: 1850–2014
- Tropical cyclones extracted by the UZ tracker
  - Location: [data/RGTracks-20Cv1_UZ_1850-2014.csv](https://github.com/jeremychleung/RGTracks-20C/blob/main/data/RGTracks-20Cv1_UZ_1850-2014.csv)
  - Temporal coverage: 1850–2014
<br />

**Data format**
-----
- The dataset provides detailed TC information, including location (longitude, latitude, hemisphere and basin), time (year, month, day, hour and season), and intensity (minimum SLP and maximum wind10), with a temporal resolution of 6 hours, spanning from 1850 to 2014 and covering the globe.
- Two data file are provided. One of it contains results based on the OWZ tracker, and the other contains that based on the UZ algorithm.
- Descriptions of each CSV data column:
  - _track_id_: Storm Identifier. 
  - _year_: Year (in UTC) when the TC occurs. All points are provided at 6 hour intervals.
  - _month_: Month (in UTC) when the TC occurs. All points are provided at 6 hour intervals.
  - _day_: Day (in UTC) when the TC occurs. All points are provided at 6 hour intervals.
  - _hour_: Hour (in UTC) when the TC occurs. All points are provided at 6 hour intervals.
  - _lon_: Longtiude of the TC position (unit: deg east)
  - _lat_: Latitude of the TC position (unit: deg north)
  - _slp_: Minimum sea level pressure (unit: hPa or mb)
  - _wind10_: Maximum 10-m wind speed (unit: m/s)
  - _hemisphere_: _N_ refers to Northern Hemisphere; _S_ refers to Southern Hemisphere
  - _basin_: Basins include: North Atlantic (_NATL_), Eastern North Pacific (_ENP_), Western North Pacific (_WNP_), North Indian (_NI_), South Indian (_SI_), Southern Pacific (_SP_), South Atlantic (_SA_)
  - _season_: TC season that the TC occurs (unit: year)
  - _slp_c_: Minimum sea level pressure after bias correction (unit: hPa or mb)
  - _wind10_c_: Maximum 10-m wind speed after bias correction (unit: m/s)
<br />

**Citation**
-----
If you use the RGTracks-20C in a publication or for any other purposes, please cite 
- Ye G., Leung J.C.H., Dong W., Xu J., Li W., Qian W., Zhang B. A Reanalysis-Based Global Tropical Cyclone Tracks Dataset for the Twentieth Century. Scientific Data (under review). <!-- https://doi.org/10.1007/s00382-022-06142-2 -->
- Zenodo archive: https://doi.org/10.5281/zenodo.8410597
<br /> 

**References**
-----
- Ye G., Leung J.C.H., Dong W., Xu J., Li W., Qian W., Zhang B. A Reanalysis-Based Global Tropical Cyclone Tracks Dataset for the Twentieth Century. Scientific Data (under review). <!-- https://doi.org/10.1007/s00382-022-06142-2 -->
<!-- - Leung, J.CH., Qian, W. Monitoring the Madden–Julian oscillation with geopotential height. Clim Dyn 49, 1981–2006 (2017). https://doi.org/10.1007/s00382-016-3431-x -->
<!-- - Wheeler, M.C., Hendon, H.H. An All-Season Real-Time Multivariate MJO Index: Development of an Index for Monitoring and Prediction. Mon Weather Rev 132:1917–1932 (2004). https://journals.ametsoc.org/view/journals/mwre/132/8/1520-0493_2004_132_1917_aarmmi_2.0.co_2.xml -->
<br /> 

**Contact**
-----
If you have any questions about the data, feel free to contact Ms. Guiling Ye (yegling3@mail2.sysu.edu.cn) and Dr. Jeremy Leung (chleung@pku.edu.cn or liangzx@gd121.cn).
<br /> 
