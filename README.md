# maryland-precipitation-crashes
CMSC 320 project studying the association between daily precipitation and reported Maryland motor vehicle crashes during 2019–2023.


## Crash data (2019-2023)

**How I collected the data: Each dashboard was downloaded one year at a time, then stacked together and cleaned. 

**Files to use: crash_data/md_crashes_by_county_month.csv -> this file holds all the cleaned crash data for each country by the month in the year over the range

**Charts: crash_charts has the total crashes by county and a motnhly crash chart for each country

**Notes:
- Weather data should be merged with the county, year, and month
- Crashes in 2020 are 18% lower than those in 2019 (less cars on the road, not weather related)
- Large counties need to be taken into consideration
- All crash data, raw and cleaned, is in the marylnad_crash_data folder

Category1:Population vs. Crashes Analysis

- Graph is in the crash_data file

We compared each county's total crashes (2019-2023) with its average population over the same years using Pearson and Spearman correlation.

Result: Strong positive association (Pearson r = 0.927, Spearman rho = 0.974, both p < 0.001). 
