# mjr-ag
MJR Ag forecasting

# Overview

This is a work in progress.

## MVP

Delta of crops growing and their condition, in order to try to front run repricings and the weekly crop progress report. In essence, we are predicting weekly crop conditions.

Possible attempts (not fully thought out):

1. Visualization with delta: collect current crop progress reports and plot the change each week, along with YoY change. Given that we expect a weaker La Nina year than last year (reverting to baseline), we should expect a closer to average result than last year if the major impact variables is weather related. By seeing if progress is increasing faster or slower than normal we can position ourselves accordingly, especially with respect to major contracts/futures expiry.
2. Regression against previous crop progress reports: collect as much crop progress reports as we can, and attempt to fit crop progress over time for each year. Plot crop progress reports against regression, try to determine predictive power.
3. Statistics against previous crop progress reports: binning, averages, try to determine patterns in the crop progress report data with some predictive power.
4. El Nino/La Nina statistics: track historical El Nino/La Nina/neutral years and group crop progress report data according to their grouping years. For finer detail, track the classification by month especially looking for periods where La Nina gives way to neutral periods in the Northern Hemisphere summer/fall.
5. Weather modeling: pull in global weather model output to show temperature/rainfall/cloud cover(proxy for sunlight) over growing areas. Attempt to predict crop progress reports if possible - this might require some sort of visual ML on historical data, which could put it out our ability to attempt in this time.
6. Western hemisphere predictions: attempt to predict crop progress for the Western Hemisphere, which is most strongly affected by El Nino/La Nina effects.

## How we profit

By predicting the Progress Reports, we can position ourselves before the market.

# Data

## Required Data

* Windy data on weather patterns (wind, precipitation, jetstream)

* USDA crop planting by jurisdiction

## Optional Data




# Resources

* [Background information for planting season 2022](https://www.severe-weather.eu/long-range-2/la-nina-ocean-collapse-winter-spring-weather-2022-usa-el-nino-forecast-fa/)

* [USDA Weekly Crop Progress Report](https://usda.library.cornell.edu/concern/publications/8336h188j)

* [Windy](https://www.windy.com/) - Data on wind conditions

* [USDA National Crop Progress Publications](https://www.nass.usda.gov/Publications/National_Crop_Progress/)

* [Weather Forecasting 7 days out has 80% accuracy](https://scijinks.gov/forecast-reliability/)
