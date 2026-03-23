# environMAP Dataset

| Variable Name                                               | Spatial Resolution | Neighbourhood (Diameter) [m]  | Temporal Coverage                      | Units |
|-------------------------------------------------------------|--------------------|-------------------------------|----------------------------------------|-------|
| **Grey Spaces: World Settlement Footprint (WSF) 3D [^1]**   |                    |                               |                                        |       |
| Average Building Height                                     | 90 m               | None                          | static with data from 2010–2015        | dm    |
| Building Fraction                                           | 90 m               | None                          | static with data from 2010–2015        | %     |
| Total Building Area                                         | 90 m               | None                          | static with data from 2010–2015        | m²    |
| Total Building Volume                                       | 90 m               | 90 / 1000 / 2000              | static with data from 2010–2015        | m³    |
| Total Building Volume Variance                              | 90 m               | 1000 / 2000                   | static with data from 2010–2015        | m³    |
| Total Building Volume Standard Deviation                    | 90 m               | 1000 / 2000                   | static with data from 2010–2015        | m³    |
| **Green Spaces: Tree Cover [^2] and NDVI [^3]**             |                    |                               |                                        |       |
| Normalised Difference Vegetation Index (NDVI)               | 300 m              | None                          | Every 10 days (2013–2021)              |       |
| Tree Cover                                                  | 30 m               | 30 / 300 / 500 / 1000 / 3000 / 5000 | 2010                             | %     |
| **Blue Spaces: Distance to Waterbodies [^4]**               |                    |                               |                                        |       |
| Surrounding Waterbodies                                     | 30 m               | 300 / 500 / 1000 / 3000 / 5000 | Yearly (1984–2021)                    |       |
| Surrounding Waterbodies Gaussian Filter                     | 30 m               | 300 / 500 / 1000 / 3000 / 5000 | Yearly (1984–2021)                    | %     |
| **Light Exposure: Night-time Lights [^5] and Solar Radiation** [^6] [^7] |       |                                |                                       |       | 
| Night-time Lights (NTL)                                     |  1000 m	           | None	                        | Yearly (1992-2018)                    |    dm | 	
| SARAH-2 | 0.05° | None | Monthly (2005-2020) | W/m2 | 
| Solar Radiation	| 	300 m	| None	| Weekly (static)	| W/m² | 
| **Elevation: Copernicus Digital Elevation Model (DEM) [^8]** |                   |                               |                                        |       | 
| Elevation	|  30 m	| 30/300/500/1000/3000/5000	| static with data from 2010-2015, 2019 | 	m | 
| Elevation Range	| 30 m	| 	30/300/500/1000/3000/5000	| static with data from 2010-2015, 2019 |  	m | 
| Elevation Standard Deviation | 	30 m	| 	30/300/500/1000/3000/5000	| static with data from 2010-2015, 2019 | 	m | 
| Slope	 | 	30 m | 	30/300/500/1000/3000/5000/7500	| static with data from 2010-2015, 2019 | 	° | 
| Aspect | 	30 m | 		None	| static with data from 2010-2015, 2019 | 	° | 
| Terrain Ruggedness Index (TRI)	|  30 m	 | 	90	| 	static with data from 2010-2015, 2019 | |
| Roughness	|	30 m |	90	|	static with data from 2010-2015, 2019 | |
| **Weather Patterns and Extreme Weather Data [^9]**                             |                    |                              |                                                                                                                 |        |
| Cloud cover (total, high, medium and low clouds)                               | 0.25°              | None                         | Hourly; Monthly means and standard deviation                                                                    |        |
| Temperature, 2 m                                                               | 0.25°              | None                         | Hourly; Diurnal range; Daily and monthly mean, maximum and minimum                                              | °C     |
| Temperature, dewpoint                                                          | 0.25°              | None                         | Hourly; Daily and monthly diurnal range, mean, maximum and minimum; Monthly diurnal and mean standard deviation | °C     |
| Wet-bulb globe temperature (WBGTmax)                                           | 0.25°              | None                         | Daily and monthly mean; Monthly standard deviation                                                              | °C     |
| Precipitation volume                                                           | 0.25°              | None                         | Hourly; Daily and monthly mean; Monthly standard deviation                                                      | mm/day |
| Precipitation duration                                                         | 0.25°              | None                         | Daily and monthly duration; Monthly standard deviation; Daily duration of maximum events [h]                    | h/day  |
| Total number of wet days (≥1 mm)                                               | 0.25°              | None                         | Monthly total number of wet days (≥1 mm)                                                                        | days   |
| Simple Precipitation Intensity Index (mean on wet days ≥1 mm during the month) | 0.25°              | None                         | Monthly                                                                                                         | mm/day |
| TXx: Monthly maximum value of daily maximum temperature                        | 0.25°              | None                         | Monthly                                                                                                         | °C     |
| TNx: Monthly maximum value of daily minimum temperature                        | 0.25°              | None                         | Monthly                                                                                                         | °C     |
| TNn: Monthly minimum value of daily minimum temperature                        | 0.25°              | None                         | Monthly                                                                                                         | °C     |
| TX90p: Percentage of warm days (>90th percentile)                              | 0.25°              | None                         | Monthly                                                                                                         | %      |
| TN90p: Percentage of warm nights (>90th percentile)                            | 0.25°              | None                         | Monthly                                                                                                         | %      |
| TX10p: Percentage of cold days (<10th percentile)                              | 0.25°              | None                         | Monthly                                                                                                         | %      |
| TN10p: Percentage of cold nights (<10th percentile)                            | 0.25°              | None                         | Monthly                                                                                                         | %      |
| Warm spell duration index                                                      | 0.25°              | None                         | Yearly                                                                                                          | days   |
| Cold spell duration index                                                      | 0.25°              | None                         | Yearly                                                                                                          | days   |
| WBGTmax90p: Percentage of days with extreme WBGTmax (>90th percentile)         | 0.25°              | None                         | Monthly                                                                                                         | %      |
| CWD: Maximum number of consecutive wet days                                    | 0.25°              | None                         | Monthly                                                                                                         | days   |
| Rx5D: Monthly highest 5-day precipitation amount                               | 0.25°              | None                         | Monthly                                                                                                         | mm     |
| R10mm: Heavy precipitation days (≥10 mm)                                       | 0.25°              | None                         | Monthly                                                                                                         | days   |
| R20mm: Very heavy precipitation days (≥20 mm)                                  | 0.25°              | None                         | Monthly                                                                                                         | days   |
| R75pTOT: Moderate wet days per month (≥75th percentile)                        | 0.25°              | None                         | Monthly                                                                                                         | days   |
| R95pTOT: Very wet days per month (≥95th percentile)                            | 0.25°              | None                         | Monthly                                                                                                         | days   |
|**Atmospheric Composition Data: Air Quality and Pollution [^10]**                |                    |                              |                                                                                                                |        |
| Sea salt aerosol mixing ratios                     | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Dust aerosol mixing ratios                         | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Hydrophilic organic matter aerosol mixing ratio    | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Hydrophobic organic matter aerosol mixing ratio    | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Hydrophilic black carbon aerosol mixing ratio      | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Hydrophobic black carbon aerosol mixing ratio      | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Sulphate aerosol mixing ratio                      | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Nitrogen dioxide mass mixing ratio (NO₂)           | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Sulphur dioxide mass mixing ratio (SO₂)            | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/kg-1 |
| Total column carbon monoxide (CO)                  | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-2  |
| Total column formaldehyde (CH₂O)                   | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-2  |
| Total column methane (CH₄)                         | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-2  |
| Total column ozone (O₃)                            | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-2  |
| Black carbon aerosol optical depth (AOD) at 550 nm | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Dust AOD at 550 nm                                 | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Organic matter AOD at 550 nm                       | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Sea salt AOD at 550 nm                             | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Sulphate AOD at 550 nm                             | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Total AOD at 550 nm                                | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation |         |
| Particulate matter d < 1 μm (PM₁)                  | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-3  |
| Particulate matter d < 2.5 μm (PM₂.₅)              | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-3  |
| Particulate matter d < 10 μm (PM₁₀)                | 0.75°              | None                         | 3-hourly; Monthly mean and standard deviation | kg/m-3  |



[^1]:   Esch T, Brzoska E, Dech S, et al. World Settlement Footprint 3D - A first three-dimensional survey of the global building stock. Remote Sensing of Environment 2022; 270: 112877. https://doi.org/10.1016/j.rse.2021.112877.

[^2]:	Hansen MC, Potapov PV, Moore R, et al. High-resolution global maps of 21st-century forest cover change. Science 2013; 342: 850–53. https://doi.org/10.1126/science.1244693.

[^3]:	Sterckx S, Benhadj I, Duhoux G, et al. The PROBA-V mission: image processing and calibration. International Journal of Remote Sensing 2014; 35: 2565–88. https://doi.org/10.1080/01431161.2014.883094&sa=D&source=docs&ust=1715602796580134&usg=AOvVaw1abKuVnr4pQTOPHG90A7aD.

[^4]:	Pekel J-F, Cottam A, Gorelick N, Belward AS. High-resolution mapping of global surface water and its long-term changes. Nature 2016; 540: 418–22. https://doi.org/10.1038/nature20584.

[^5]:	Li X, Zhou Y, Zhao M, Zhao X. A harmonized global nighttime light dataset 1992-2018. Sci Data 2020; 7: 168. https://doi.org/10.1038/s41597-020-0510-y.

[^6]:	Muellejans H, Pavanello D, Sample T, et al. State-of-the-art assessment of solar energy technologies. 1831-9424 2022. https://doi.org/10.2760/735053.

[^7]:   Solar Radiation Product by Julien Radoux (https://maps.elie.ucl.ac.be/lifewatch/geoviewer.html?tab=sun#).

[^8]:	European Union, ESA, DLR e.V., Airbus Defence and Space GmbH. Copernicus DEM, 2022.

[^9]:   Hersbach H, Bell B, Berrisford P, et al. The ERA5 global reanalysis. Quart J Royal Meteoro Soc 2020; 146: 1999–2049. https://doi.org/10.1002/qj.3803.

[^10]:  Inness A, Ades M, Agustí-Panareda A, et al. The CAMS reanalysis of atmospheric composition. Atmos. Chem. Phys. 2019; 19: 3515–56. https://doi.org/10.5194/acp-19-3515-2019.
