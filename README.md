# Town to Planning Region Crosswalk

The ct-town-to-planning-region.csv file contains a crosswalk between 169 Connecticut towns and planning regions/county equivalents.

#### Note about FIPS Codes and County Equivalents

In 2022, the Census Bureau adopted Connecticut's nine planning regions as county equivalents- new county-level geographies for Connecticut for statistical purposes, replacing Connecticut's eight counties in Census Bureau data products. The county equivalents have new FIPS codes. 

Census Bureau data and publications will transition to using the county equivalents instead of counties throughout 2023-2024. To help ease this transition, this crosswalk includes town FIPS codes for both the original counties and the new county equivalents. 

Towns therefore have two FIPS identifiers. The town boundaries did not change.
- town_fips_20 include the FIPS code from its county (county_fips_20)
- town_fips_22 include the FIPS code from its county equivalent/planning region (ce_fips_22)
