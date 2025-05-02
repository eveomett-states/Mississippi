# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Mississippi Election Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/mississippi-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2022-mississippi-congressional-districts-approved-plan/): 2022 Congressional Districts Approved Interim Plan

[State House District data](https://redistrictingdatahub.org/dataset/2022-mississippi-house-of-representatives-approved-plan/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-mississippi-senate-districts-approved-plan/): 2022 State Senate Districts Interim Plan from

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-mississippi-precinct-and-election-results/): VEST 2020 precinct and election results

[2019 election data](https://redistrictingdatahub.org/dataset/vest-2019-mississippi-precinct-and-election-results/): VEST 2019 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-mississippi-precinct-and-election-results/): VEST 2018 precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-mississippi-precinct-and-election-results/): VEST 2016 precinct and election results

[County data](https://redistrictingdatahub.org/dataset/mississippi-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

# **Processing**

Demographic data were aggregated from the census block level and precincts were assigned to districts using [MGGG's proration software](https://github.com/mggg/maup). Election data were also prorated onto VTDs from the original precinct shapefile using the `maup` package.

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code of 2020
- `COUNTYFP20`: County FIPS code of 2020
- `GEOID20`: VTD FIPS code of 2020
- `NAME20`: Voting tabulation district name of 2020
- `VTDST20`: Voting tabulation district FIPS code of 2020
- `CD`: Congressional district ID in 2022 enacted congressional map
- `SEND`: State Senate district for 2022 State Senate Adopted Plan
- `HDIST`: State House district for 2022 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- `USS16D`: Number of votes for 2016 Democratic senate candidate
- `USS16R`: Number of votes for 2016 Republican senate candidate
- `USS16O`: Number of votes for 2016 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate
