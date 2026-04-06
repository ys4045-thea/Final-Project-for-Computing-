# Project Prosal
## Yue Shi ys4045

The project aims to examine and visualize the trend in snow cover and their implications of the ski season length across the United States for the period of 2000-2023.

## Scientific Question
How has snow cover extent and snow season length changed across the United States over the past two decades? Are potential snowmaking conditions also deteriorating in regions heavily dependent on winter tourism?

## Hypotheses
1. All study regions show declining trends in snow cover extent and snow season length between 2000 and 2023
2. Lower-latitude ranges decline faster than high-latitude ranges
3. Potential snowmaking hours with wet-bulb temperature < -2°C in the early season window have decreased

## Datasets
- **MODIS/Terra Monthly Snow Cover L3 Global 0.05Deg CMG v61** - clipped to continental U.S. (24–50°N, 66–125°W)
  https://nsidc.org/data/mod10cm/versions/61

- **MOD10A1.061 Terra Snow Cover Daily Global 500m** -clipped to continental U.S. (24–50°N, 66–125°W)
  https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD10A1?hl=zh-cn

- **SRTM 90m DEM** — elevation data for elevation-band analysis
  https://srtm.csi.cgiar.org

- **ERA5-Land Hourly Reanalysis** — 2m temperature and dewpoint temperature for wet-bulb temperature calculation
  https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land

## Analysis Summary
This project will use MODIS satellite data to visualize snow cover trends and calculate snow season length across U.S. from 2000 to 2023. ERA5-Land hourly temperature and dewpoint data will be used to derive wet-bulb temperature and estimate how potential snowmaking hours in the early ski season have changed over the same period. Results will be compared across regions and elevation bands with time-series graphs to assess where snow loss is most severe and where the winter recreation industry is becoming climatically constrained.
