# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Montana Json and Shapefile

This shapefile was processed by Professor Ellen Veomett and her students Arbie Hsu and Alusi, using the corresponding jupyter notebook. As part of the cleaning process, precincts were nested within counties and small rook adjacencies (under 30.5 m) were changed to queen adjacencies.

# **Sources**

The following obtained from [Redistricting Data Hub](https://redistrictingdatahub.org/) on June, 2024:

[Population data](https://redistrictingdatahub.org/dataset/montana-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[Congressional District data](https://redistrictingdatahub.org/dataset/2021-montana-cong-adopted-plan/): 2022 Congressional Districts Approved Interim Plan

[State House District data](https://redistrictingdatahub.org/dataset/2023-montana-house-of-representatives-districts-approved-plan/): 2022 State House Approved Interim Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2023-montana-senate-districts-approved-plan/): 2022 State Senate Districts Interim Plan from

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-montana-precinct-and-election-results/): VEST 2020 precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-montana-precinct-and-election-results/): VEST 2018 precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-montana-precinct-and-election-results/): VEST 2016 precinct and election results

[2022 county data](https://redistrictingdatahub.org/dataset/montana-county-cvap-data-2022/) 2022 Citizen Voting Age Population (CVAP) data for Montana from the 2018-2022 ACS 5-Year estimates at the County level

# **Processing**

Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `COUNTY20`: County code of 2020
- `COUNTYFP20`: County FIPS code of 2020
- `NAME20`: Voting tabulation district name of 2020
- `SOSPRECINC20`:
- `STATEFP20`: State FIPS code of 2020
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
- `ATG16D`: Number of votes for 2016 Democratic attorney general candidate
- `ATG16R`: Number of votes for 2016 Republican attorney general candidate
- `ATG20D`: Number of votes for 2020 Democratic attorney general candidate
- `ATG20R`: Number of votes for 2020 Republican attorney general candidate
- `AUD16D`: Number of votes for 2016 Democratic Auditor
- `AUD16R`: Number of votes for 2016 Republican Auditor
- `AUD20D`: Number of votes for 2020 Democratic Auditor
- `AUD20O`: Number of votes for 2020 other party's Auditor
- `AUD20R`: Number of votes for 2020 Republican Auditor
- `CSC18D`: Number of votes for 2018 Democratic Clerk of the Supreme Court
- `CSC18R`: Number of votes for 2018 Republican Clerk of the Supreme Court
- `CSC18O`: Number of votes for 2018 other party's Clerk of the Supreme Court
- `GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
- `GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
- `GOV16O`: Number of votes for 2016 other party's gubernatorial candidate
- `GOV20R`: Number of votes for 2020 Republican gubernatorial candidate
- `GOV20D`: Number of votes for 2020 Democratic gubernatorial candidate
- `GOV20O`: Number of votes for 2020 other party's gubernatorial candidate
- `HAL16D`: Number of votes for 2016 Democratic of U.S. House where district number is at large
- `HAL16O`: Number of votes for 2018 other party's of U.S. House where district number is at large
- `HAL16R`: Number of votes for 2018 Republican of U.S. House where district number is at large
- `HAL18D`: Number of votes for 2018 Democratic of U.S. House where district number is at large
- `HAL18O`: Number of votes for 2018 other party's of U.S. House where district number is at large
- `HAL18R`: Number of votes for 2018 Republican of U.S. House where district number is at large
- `HAL20D`: Number of votes for 2020 Democratic of U.S. House where district number is at large
- `HAL20R`: Number of votes for 2020 Republican of U.S. House where district number is at large
- `PRE16D`: Number of votes for 2016 Democratic President
- `PRE16O`: Number of votes for 2016 other party's President
- `PRE16R`: Number of votes for 2016 Republican President
- `PRE20D`: Number of votes for 2020 Democratic President
- `PRE20R`: Number of votes for 2020 Republican President
- `PRE20O`: Number of votes for 2020 other party's President
- `SOS16D`: Number of votes for 2016 Democratic Secretary of State
- `SOS16R`: Number of votes for 2016 Republican Secretary of State
- `SOS16O`: Number of votes for 2016 other party's Secretary of State
- `SOS20D`: Number of votes for 2020 Democratic Secretary of State
- `SOS20R`: Number of votes for 2020 Republican Secretary of State
- `SPI16D`: Number of votes for 2016 Democratic Superintendent of Public Instruction
- `SPI16R`: Number of votes for 2016 Republican Superintendent of Public Instruction
- `SPI20D`: Number of votes for 2020 Democratic Superintendent of Public Instruction
- `SPI20R`: Number of votes for 2020 Republican Superintendent of Public Instruction
- `SPI20O`: Number of votes for 2020 other party's Superintendent of Public Instruction
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
