# Iowa Liquor Sales Analysis
## Introduction
This exploratory analysis uses public data on liquor sold in Iowa and US census population data to examine sales trends. 

This analysis focuses on the ten most populous Iowa counties during 2018-2023.
The ten most populous Iowa counties (out of 100 total counties) comprise 52.6% of the adult (18+) population and represent 59% of the state's total liquor sales (by volume) to Iowa Class “E” liquor licensees–grocery stores, liquor stores, etc.

## Data Sources
Liquor Data: https://data.iowa.gov/Sales-Distribution/Iowa-Liquor-Sales/m3tr-qhgy
data.iowa.gov

Population Data: United States Census Bureau 
https://www.census.gov/quickfacts/fact/table/IA/POP010220

### Cleaning:
<ul>
  <li>Null checks</li>
  <li>Duplicate checks</li>
  <li>Filled missing values</li>
  <li>Identified and corrected recurring county name misspelling</li>
</ul>

### Processing:
<ul>
  <li>Liquor category recategorization and simplifications</li>
  <li>Calculated adult population from percent adults and total population </li>
  <li>Combined datasets to find per capita sales </li>
</ul>

### Exploration and Conclusions
Total sales and per-capita sales were measured and visualized across counties during the target period. Liquor categories present in the liquor data were cleaned and simplified. Consumption patterns of liquor types was investigated and visualized across counties and years. 

Polk county (the largest Iowa county) led sales both overall, and per-capita. Liquor sales increased slightly and steadily over time. Sales rose across counties in 2020 and 2021 and fell back into the original gradual trend in 2022 and 2023. As these data reflect wholesale prices for off-premises consumptions, it may reflect a shift away from consumption at bars and restaurants, and then back to on-premises consumption as pandemic restrictions ended. 

We see some seasonal patterns, including spikes in spring, October, and December. The most notable pattern seen across all counties is a jump in sales just before the new year and a drop in January. This may be due to the fact that we are looking at wholesale data. Stores likely stock up for December and new year celebrations and pause ordering immediately after the holidays. 

The most striking pattern noted was the consistent purchasing patterns by counties when comparing sales of vodka, whiskey, and all other liquors. Purchasing patterns are remarkably consistent by county year over year. Each county seems to have distinct preferences, and these preferences are enduring and predictable. 
Year over year, the distribution of vodka, whiskey, and all other liquors appear nearly identical. Statistical analysis could further confirm this pattern. 

### Recommendations for future work 

Track popularity of individual product across counties, markets, and over time for marketing purposes

Track state profits across products and sales to identify least and most profitable

Check whether liquor sales followed the school calendars of university sites like Johnson County to prepare for demand and for promotion timing

Quantify consistency of county purchasing patterns of vodka, whiskey and other liquors. 

Investigate whether 'vodka, whiskey, other' pattern extends to other liquor types

See [repository](https://github.com/amoutafian/iowa_liquor_project )

