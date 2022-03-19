# cluster_weather_Amsterdam
Cluster analysis of weather data in Amsterdam, 1891-1939

## Data and sources
This repository contains the data and codes for the cluster analysis of weather in Amsterdam between 1891 and 1939. The .xlsx dataset includes standardized monthly weather variables. The unit of analysis is "year/month" (e.g. 1891/1, 1895/12). The original raw data are obtained from two sources. Hourly data on temperature, air pressure, wind strength and hours without precipitation are from the HISKILM project of the Royal Netherlands Meteorological Institute. Monthly data on total and maximum precipitation and the mean of relative humidity at 8am are taken from the Statistical Yearbooks of Amsterdam. The raw data ar not provided. 

## Variables
1. z_mean_temp: mean monthly temperature (standardized)
2. z_temp_range: mean daily temperature range (standardized)
3. z_mean_press: mean monthly air pressure (standardized)
4. z_press_range: mean daily air pressure range (standardized)
5. z_dry: the monthly number of hours without any precipitation (standardized)
6. z_lightwind: the monthly number of hours with light wind (standardized)
7. z_modwind: the monthly number of hours with moderate wind (standardized)
8. z_strongwind: the monthly number of hours with strong wind (standardized)
9. z_prec_total: total monthly precipitation (standardized)
10. z_prec_max: maximum daily precipitation (standardized)
11. z_rel_hum: monthly mean of relative humidity (standardized)

## Files in the repository
1. Standardized monthly weather data
2. R codes in R markdown format
3. heatmap.png
4. barchart.png
5. Report in .pdf format

## References

Statistical Yearbooks of Amsterdam - available in .pdf format on the website of the Amsterdam City Archive: https://data.amsterdam.nl/

More information on the HISKLIM project: https://www.knmi.nl/kennis-en-datacentrum/achtergrond/recovery-and-disclosure-of-historical-meteorological-observations-hisklim

https://cdn.knmi.nl/knmi/pdf/bibliotheek/knmipubDIV/HISKLIM/HISKLIM_9.pdf

Raw data are downloadable at https://www.knmi.nl/nederland-nu/klimatologie


## Contact
katalin.buzasi@ru.nl
katalinbuzasi@weebly.com
