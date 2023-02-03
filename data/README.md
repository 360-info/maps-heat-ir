# `/data`

- `postcode-suburb-map.csv`: a data frame linking postcodes to suburbs. **The correspondence between postcodes and suburbs isn't 1:1**; this is used to make searching easier in the map.
- `news-stats-postcodes-short.csv`: a data frame of projections by postcode. Columns are:
  - `file_scenario`: Either `historical`, `rcp45` (medium emissions), `rcp85` (high emissions), or `rcpXXdiff` (where the `ens` figures represent changes from historical rather than gross figures)
  - `file_period`: Either `1995` (representing 1985 to 2005), `2030` (representing 2020 to 2040) or `2050` (representing 2040 to 2060)
  - `geo_name`: The postcode
  - `ensmean`: The average number of days (or extra days) estimated by the climate models in NARCLiM1.5.
  - `ensmax`: The highest number of days (or extra days) estimated by the climate models in NARCLiM1.5.
  - `ensmin`: The lowest number of days (or extra days) estimated by the climate models in NARCLiM1.5.