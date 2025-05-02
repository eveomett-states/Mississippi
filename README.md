# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Mississippi Json and  Shapefile

This shapefile was processed by Professor Ellen Veomett and her student Arbie Hsu using the corresponding jupyter notebook.  As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies. 

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/mississippi-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2022-mississippi-congressional-districts-approved-plan/): 2022 Congressional Districts Approved Interim Plan

[State House District data](https://redistrictingdatahub.org/dataset/2022-mississippi-house-of-representatives-approved-plan/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-mississippi-senate-districts-approved-plan/): 2022 State Senate Districts Interim Plan from

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-mississippi-precinct-and-election-results/): VEST 2018 precinct and election results

[County data](https://redistrictingdatahub.org/dataset/mississippi-county-pl-94171-2020/): from 2020 Census Redistricting Data (P.L. 94-171) Shapefiles

And the following was obtained on May 2, 2025:

[2023 election data](https://redistrictingdatahub.org/dataset/mississippi-2023-general-election-precinct-level-results-and-boundaries/): Mississippi 2023 General Election Precinct-Level Results and Boundaries

We would have liked to include more election data, but were unable to clean the following shapefiles: [2022 election data](https://redistrictingdatahub.org/dataset/mississippi-2022-general-election-precinct-level-results-and-boundaries/), [2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-mississippi-precinct-and-election-results/), [2019 election data](https://redistrictingdatahub.org/dataset/vest-2019-mississippi-precinct-and-election-results/), [2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-mississippi-precinct-and-election-results/).  They all resulted in topology errors.

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP18`: State FIPS code of 2018
- `COUNTYFP18`: County FIPS code of 2018
- `GEOID18`: VTD FIPS code of 2018
- `NAME18`: Voting tabulation district name of 2018
- `VTDST18`: Voting tabulation district FIPS code of 2018
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
- `AGR23D`: Number of votes for 2023 Democratic Commissioner of Agriculture & Commerce candidate
- `AGR23R`: Number of votes for 2023 Republican Commissioner of Agriculture & Commerce candidate
- `ATG23D`: Number of votes for 2023 Democratic Attorney General candidate
- `ATG23R`: Number of votes for 2023 Republican Attorney General candidate
- `AUD23D`: Number of votes for 2023 Democratic State Auditor candidate
- `AUD23R`: Number of votes for 2023 Republican State Auditor candidate
- `GOV23D`: Number of votes for 2023 Democratic Gubernatorial candidate
- `GOV23R`: Number of votes for 2023 Republican Gubernatorial candidate
- `GOV23O`: Number of votes for 2023 other party's Gubernatorial candidate
- `INS23D`: Number of votes for 2023 Democratic Commissioner of Insurance candidate
- `INS23R`: Number of votes for 2023 Republican Commissioner of Insurance candidate
- `LTG23D`: Number of votes for 2023 Democratic Lieutenant Governor candidate
- `LTG23R`: Number of votes for 2023 Republican Lieutenant Governor candidate
- `SOS23D`: Number of votes for 2023 Democratic Secretary of State candidate
- `SOS23R`: Number of votes for 2023 Republican Secretary of State candidate
- `TRE23D`: Number of votes for 2023 Democratic State Treasurer candidate
- `TRE23R`: Number of votes for 2023 Republican State Treasurer candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate

