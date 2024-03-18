cars_SMC.csv 
- source: https://data.ca.gov/dataset/vehicle-fuel-type-count-by-zip-code
- I used the 2023 dataset and filtered to just San Mateo County

zipcodes_SMC.csv 
- source: https://www.ciclt.net/sn/clt/capitolimpact/gw_ziplist.aspx?ClientCode=capitolimpact&State=ca&StName=&StFIPS=&FIPS=06081 
- Just all the SMC zipcodes and corresponding city names. I copied and pasted the data from the website into an excel file and exported it as a csv

SMC_zipcodes_shapefile.zip 
- source: https://geodata.lib.berkeley.edu/catalog/stanford-gm175wm1954
- Geopandas data for shape of each SMC zipcode

income_SMC_counts.csv
- source (original census data):
- source (Eden's compiled version): https://raw.githubusercontent.com/edenmhuang/DataJam_2024/main/CA_Household_Income_2022.csv
- I took the census data that Eden had organized, converted the percentages from objects into floats, then multiplied by the household count to get counts of each income bracket by zip code
