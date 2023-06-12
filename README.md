# Colorado AirNow + Purple Air Calibration Repository

This project analyzes the calibration parameters for the [Purple Air real-time air quality monitor](https://www2.purpleair.com/).

## Analysis Methodology

The analysis is broken up into several Jupyter notebooks.

| notebook | description | link |
|---------:|:------------|:----:|
| API extraction | extracts data from the EPA AN dataset | [./preprocessing/AirNow_API_extraction.ipynb](./preprocessing/AirNow_API_extraction.ipynb) |
| data analysis| initial analysis | [./analysis/analysis_01.ipynb](./preprocessing/AirNow_API_extraction.ipynb) |
| -- | --| -- |

## Data Sets

EPA AQI API (historical):
* https://aqs.epa.gov/aqsweb/documents/data_api.html

EPA AirNow API (real-time):
* https://docs.airnowapi.org


The analysis uses the following datasets:

| dataset | description | link |
|---------:|:------------|:----:|
| -- | -- | -- |


**About PurpleAir**

[PurpleAir](https://www2.purpleair.com) is a real-time air quality monitoring system that uses proprietary sensors to measure particle pollution in the air. The sensors are available for indoor and outdoor use and are priced at a fraction of what you pay for a commercial sensor. The readings provided by PurpleAir may differ from those provided by AirNow.gov, which uses Environmental Protection Agency standards to calculate its air quality index (AQI) score. PurpleAir’s numbers are measured in real-time, while AirNow’s figures are updated hourly but delayed compared to PurpleAir. The sensors used by PurpleAir differ from those used by AirNow, which measure particulate matter by drawing air through a filter and then weighing the filter. PurpleAir’s sensors use a laser particle counter to measure the number of airborne particles and then employ an algorithm to calculate a mass concentration based on the count. 

**About AirNow**

[AirNow](https://gispub.epa.gov/airnow/) is a program developed by the U.S. Environmental Protection Agency (EPA) that provides information about air quality in the United States, Canada, and Mexico. The program includes daily air quality forecasts, maps of current air quality conditions, and real-time air quality data from monitoring stations across the country. The AirNow program also provides information about air quality and health, including the Air Quality Index (AQI), which is a color-coded scale used to communicate daily air pollution levels and associated health effects. The program has a [mobile app](https://apps.apple.com/us/app/epa-airnow/id467653238) that provides a simple interface for quickly checking the current and forecast air quality information for planning daily activities and protecting one's health. The AirNow program has guidelines for data use, which apply to data available from the AirNow program, including AirNow.gov, AirNow-Tech, and the AirNow API. 
