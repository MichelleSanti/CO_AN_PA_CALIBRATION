These notebooks contain code to download and extract data 
- AirNow_API_example_extraction notebook extracts pm2.5 data and downloads it from the EPA API website
- AirNow_data_loading notebook does the same task as the AirNow_API_extraction but loops through from the payloads text
- AirNow_payloads text contains the station information and parameters 
- AirNow_combined_data takes the individual yearly csv files and combines them to form 1 file with data beginning from 2017 to 2023  
