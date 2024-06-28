Overview:
This project utilizes data from NOAA’s Storm Events Database, which lists major weather-related storm events since 1950. For this exercise, we are using a subset of the data from the year 1991.

Dataset:
The dataset can be accessed via the following link: https://www1.ncdc.noaa.gov/pub/data/swdi/stormevents/csvfiles/StormEvents_details-ftp_v1.0_d1991_c20220425.csv.gz

This dataset contains over 50 variables. However, for our assignment, we will focus on the following 8 variables:

Variables Used and their Definitions:

BEGIN_YEARMONTH | The year and month that the event began            
EPISODE_ID | An ID assigned by the National Weather Service (NWS) to denote the storm episode; episodes may contain multiple events        
STATE | The state name where the event occurred         
STATE_FIPS | A unique number (State Federal Information Processing Standard) assigned to the state by the National Institute for Standards and Technology (NIST)        
CZ_NAME | Name of the county or zone       
CZ_TYPE | Indicates whether the event happened in a county/parish (C), NWS public forecast zone (Z), or marine area (M)        
CZ_FIPS | A unique number (County Federal Information Processing Standard) assigned to the county by the National Institute for Standards and Technology (NIST)          
EVENT_TYPE | The type of event that occurred, such as lightning, blizzard, flood, etc          
