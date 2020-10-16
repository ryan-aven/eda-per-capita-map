# eda-per-capita-map
Mapping project for FY20 EDA data

This was a project used to identify per-capita funds for fiscal year 2020 within the Economic Development Administration. Analysis was fairly straightforward, with compiled estimates of approved EDA grants by state/territory (and the District of Columbia) divided by the estimated population within each state. No computations were actually included within the R file - these were done beforehand in Excel.

The project was done in R, primarily relying on leaflet and tigris maps, using the instructions laid out by Andrew Ba Tran here:
https://learn.r-journalism.com/en/mapping/census_maps/census-maps/

Estimates for population were based off of 2019 census files, located here:
https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html

Unfortunately, at this time these numbers are unofficial so I'm unable to upload the map itself but if at some point EDA releases a public data file I can provide more concrete figures.

-Ryan Aven
