# Oregon Election Shapefiles
This shapefile was compiled by Kevin Rancik with the help of Steve Gerontakis and was used by The Oregonian. It was processed and verified by members of the Metric Geometry and Gerrymandering Group.

## Sources
The Oregon precinct shapefile was obtained from [Kevin Rancik's personal website](http://www.kevinrancik.com/elections/Oregon/eOregon.html). Rancik and Gerontakis obtained the raw county-level precinct boundaries from local county elections offices and county clerks, documented in detail [here](http://www.kevinrancik.com/elections/Oregon/e2018_11/E2018_Oregon_Metadata.pdf). Election results for 2016 and 2018 were obtained from the [MIT Election Data and Science Lab (MEDSL)](https://electionlab.mit.edu). 2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for Oregon along with congressional and state legislative districts were downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).

## Processing
Precinct election returns were cleaned by MGGG staff in order to join them to the precinct shapefile. Ceratin precincts in the shapefile and in the results were merged in order to reconcile discrepencies. Demographic data was aggregated from the block level using [MGGG’s proration software](https://github.com/mggg/maup). Congressional and state legislative district IDs were assigned to precincts also using this package.

## Metadata
* `State`: State name
* `County`: County name
* `Precinct`: Precinct ID
* `Pct_Name`: Precinct name
* `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
* `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
* `GOV18I`: Number of votes for 2018 Independent gubernatorial candidate
* `GOV18L`: Number of votes for 2018 Libertarian gubernatorial candidate
* `GOV18C`: Number of votes for 2018 Constitution party gubernatorial candidate
* `USH18D`: Number of votes for 2018 Democratic US House candidates
* `USH18R`: Number of votes for 2018 Republican US House candidates
* `PRES16D`: Number of votes for 2016 Democratic presidential candidate
* `PRES16R`: Number of votes for 2016 Republican presidential candidate
* `PRES16L`: Number of votes for 2016 Libertarian presidential candidate
* `PRES16G`: Number of votes for 2016 Green Party presidential candidate
* `SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `USH16D`: Number of votes for 2016 Democratic US House candidates
* `USH16R`: Number of votes for 2016 Republican US House candidates
* `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
* `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
* `GOV16I`: Number of votes for 2016 Independent gubernatorial candidate
* `GOV16L`: Number of votes for 2016 Libertarian gubernatorial candidate
* `AG16D`: Number of votes for 2016 Democratic attorney general candidate
* `AG16R`: Number of votes for 2016 Republican attorney general candidate
* `SOS16D`: Number of votes for 2016 Democratic secretary of state candidate
* `SOS16R`: Number of votes for 2016 Republican secretary of state candidate
* `SOS16I`: Number of votes for 2016 Independent secretary of state candidate
* `SOS16G`: Number of votes for 2016 Green Party secretary of state candidate
* `SOS16L`: Number of votes for 2016 Libertarian secretary of state candidate
* `CD`: Congressional district ID
* `HDIST`: State House district ID
* `SEND`: State Senate district ID
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census

## Projection
This shapefile uses a NAD83 Oregon North projection (EPSG: 2338).

## Rating 
We give this shapefile an A rating. While compiled by private individuals, all original sources are government officials and MGGG staff have performed quality assurance.
