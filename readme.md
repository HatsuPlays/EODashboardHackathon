# Objective
- Can you develop 2-3 globally applicable “proxies” that characterize the impact of the pandemic on air quality and/or socio-economic activities?
 How can you integrate different proxies into an integrated economic indicator? Use Earth observation data from at least two of the three regions
 for the developed proxies, ensuring the same assessment can be performed in the USA/Europe/Asia. 
# Introduction

# Links
- Could include different studies here
# TODO List
1.) Come up with a specific proxy idea
2.) Collect the relevant data needed for the idea
3.) Test the data and theory using the Europe datasets...
3.1) On major cities (London)
3.2) Smaller sections of the continment
3.3) Compare the data points to the other parts of the region, or major vs. minor locations
4.) Test the data and theory using the USA datasets.
4.1) On major cities (Los Angeles)
4.2) Smaller sections of the continment
4.3) Compare the data points to the other parts of the region, or major vs. minor locations
5.) Test the data and theory using the Asia datasets.
5.1) On major cities (Beijing)
5.2) Smaller sections of the continment
5.3) Compare the data points to the other parts of the region, or major vs. minor locations
6.) Tie everything together to tell a story
7.) Create graphs and different charts that prove the claim
8.) Draw any conclusions and suggestions using the proxy
9.) If possible, use another proxy that combines with the existing one
# Ideas
- Density of C02 throughout 2020
- - Compare it to previous years
- The effects of air quality on different socioecononmic activities
- crops unfarmed
- 

# API Links
## Guidelines for Data Contributors
- https://github.com/NASA-IMPACT/covid-api/blob/master/guidelines/README.md
## API Usage
- https://github.com/NASA-IMPACT/covid-api/blob/master/guidelines/api-usage.md
## Data Usage
- https://github.com/NASA-IMPACT/covid-api/blob/master/guidelines/data-usage.md
## API Documentation
- https://8ib71h0627.execute-api.us-east-1.amazonaws.com/docs
## Different Sites
These are the different spotlight areas that are available along with their metadata. Appending a side id from the /sites endpoint to the /datasets endpoint will return all the datasets that are available for that specific spotlight.
- https://8ib71h0627.execute-api.us-east-1.amazonaws.com/v1/sites
## Endpoint
- https://8ib71h0627.execute-api.us-east-1.amazonaws.com/v1/
## Global Spotlight Data
This will return all of the global spotlights. These are also included in the datasets that are specific to a spotlight.
- https://8ib71h0627.execute-api.us-east-1.amazonaws.com/v1/datasets/global
## Other information
{date} should be in the format YYYYMM if the timeUnit is month
{date} should be in the format YYYY_MM_DD if the value of timeUnit is day
## Example Endpoint
- https://8ib71h0627.execute-api.us-east-1.amazonaws.com/v1/9/421/193@1x?url=s3://covid-eo-data/bm_500m_daily/VNP46A2_V011_be_2020_01_01_cog.tif&resampling_method=nearest&bidx=1&rescale=0%2C100&color_map=viridis
This URL requests data from the 'nightlights-viirs' data for Beijing, with the coordinates z=9, x = 421, z = 193, and on the date January 1st 2020