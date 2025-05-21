# Cleaning the shorebird survey data 

## Raw Data

ARCTIC SHOREBIRD DEMOGRAPHICS NETWORK [https://doi.org/10.18739/A2222R68W](https://doi.org/10.18739/A2222R68W)

Data set hosted by the [NSF Arctic Data Center](https://arcticdata.io) data repository 

Field data on shorebird ecology and environmental conditions were collected from 1993-2014 at 16 field sites in Alaska, Canada, and Russia.

![Shorebird, copyright NYT](https://static01.nyt.com/images/2017/09/10/nyregion/10NATURE1/10NATURE1-superJumbo.jpg?quality=75&auto=webp)

Data were not collected every year at all sites. Studies of the population ecology of these birds included nest-monitoring to determine the timing of reproduction and reproductive success; live capture of birds to collect blood samples, feathers, and fecal samples for investigations of population structure and pathogens; banding of birds to determine annual survival rates; resighting of color-banded birds to determine space use and site fidelity; and use of light-sensitive geolocators to investigate migratory movements. 

Data on climatic conditions, prey abundance, and predators were also collected. Environmental data included weather stations that recorded daily climatic conditions, surveys of seasonal snowmelt, weekly sampling of terrestrial and aquatic invertebrates that are prey of shorebirds, live trapping of small mammals (alternate prey for shorebird predators), and daily counts of potential predators (jaegers, falcons, foxes). Detailed field methods for each year are available in the `ASDN_protocol_201X.pdf` files. All research was conducted under permits from relevant federal, state, and university authorities.

See `01_ASDN_Readme.txt` provided in the [course data repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-spring-2024-class-data) for full metadata information about this data set.

## Cleaned Dataset

**DATA & FILE OVERVIEW**

1. File List: 

- `all_cover_fixed_CARMENHOYT.csv`: a .csv file containing the cleaned version of the original `ASDN_Snow_Survey.csv`

2. Relationship between files, if important:

Single file.

3. Additional related data collected that was not included in the current
data package:

N/A

4. Are there multiple versions of the dataset? 

The original `ASDN_Snow_Survey.csv` can be found in the [bred-meds213-data-cleaning repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-data-cleaning/tree/main/data/raw). This is a subset of the dataset hosted by the [NSF Arctic Data Center](https://arcticdata.io).

**DATA-SPECIFIC INFORMATION FOR:**

For the file `data/processed/all_cover_fixed_CARMENHOYT.csv`: 

1. Number of variables: 11

2. Number of cases/rows: 42048

3. Variable List:

Column Name   | Definition                                                
------------- | ---------------------------------------------------------
Site          | Four-letter code of site at which data were collected        
Year          | Year in which data were collected               
Date          | Date on which data were collected               
Plot          | Name of study plot on which survey was conducted             
Location      | Name of dedicated snow-survey location, if applicable 
Snow_cover    | Percent cover of snow, including slush
Water_cover   | Percent cover of water
Land_cover    | Percent cover of exposed land
Total_cover   | Total sum (to check the above percents; should always sum to 100)
Observer      | Person who conducted the survey
Notes         | Any relevant comments on the survey

4. Missing data codes: NA

5. Specialized formats or other abbreviations used: 

Code	Site name	Location	Latitude	Longitude	Total Study Plot Area (ha)
barr	Barrow	Alaska, USA	71.3	-156.6	220.4
burn	Burntpoint Creek	Ontario, Canada	55.2	-84.3	63.0
bylo	Bylot Island	Nunavut, Canada	73.2	-80.0	723.6
cakr	Cape Krusenstern	Alaska, USA	67.1	-163.5	54.1
cari	Canning River Delta	Alaska, USA	70.1	-145.8	722.0
chau	Chaun River Delta	Chukotka, Russia	68.8	170.6	248.2
chur	Churchill	Manitoba, Canada	58.7	-93.8	866.9
coat	Coats Island	Nunavut, Canada	62.9	-82.5	1239.1
colv	Colville River Delta	Alaska, USA	70.4	-150.7	324.8
eaba	East Bay	Nunavut, Canada	64.0	-81.7	1205.5
iglo	Igloolik	Nunavut, Canada	69.4	-81.6	59.8
ikpi	Ikpikpuk	Alaska, USA	70.6	-154.7	174.1
lkri	Lower Khatanga River	Krasnoyarsk, Russia	72.9	106.1	270.9
made	Mackenzie River Delta	Northwest Territories, Canada	69.4	-135.0	667.3
nome	Nome	Alaska, USA	64.4	-164.9	90.1
prba	Prudhoe Bay	Alaska, USA	70.3	-148.6	120.0

**SHARING/ACCESS INFORMATION**

1. Licenses/restrictions placed on the data:

N/A

2. Links to publications that cite or use the data:



3. Links to other publicly accessible locations of the data:



4. Links/relationships to ancillary data sets: <any supplementary data sources 
that support analysis or classification of the datasets, eg., plant taxonomy table.)>

5. Was data derived from another source? If yes, list source(s):

The original `ASDN_Snow_Survey.csv` can be found in the [bred-meds213-data-cleaning repository](https://github.com/UCSB-Library-Research-Data-Services/bren-meds213-data-cleaning/tree/main/data/raw). This is a subset of the dataset hosted by the [NSF Arctic Data Center](https://arcticdata.io).

6. Recommended citation for the project:

Lanctot, RB, SC Brown, and BK Sandercock. 2017. Arctic Shorebird Demographics Network. NSF Arctic Data Center. doi: INSERT HERE. 