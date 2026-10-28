### Michael Pitts
Undergraduate at CU Boulder studying Geography w/ GIS emphasis, minor in Atmospheric and Oceanic Science. Currently working on GIS project for the community of Beulah Valley, Colorado to help recover after the Aspen Acres Fire. 

![Key West](https://www.keysseaplanes.com/wp-content/uploads/2017/11/key-west-feat-300-200.jpg "Key West")

### Contact Information
* michael.pitts@colorado.edu
* [www.linkedin.com/in/michaelpitts21](www.linkedin.com/in/)

### Lake Peachtree
Map of Lake Peachtree located in Peachtree City, Georgia.

<embed type="text/html" src="img/lakeptc.html" width="600" height="600">


## Temperature Trend in Peachtree City, Georgia

### Overview

This project examines long-term changes in annual average temperature in Peachtree City, Georgia. Historical climate observations from Atlanta Regional Airport-Falcon Field were used to calculate annual average temperature and identify if a long-term trend exists. Unfortunately, data at this site only goes back to 1994 but is the most reliable data source in Peachtree City. 

### Data and Methods

I used historical climate data from NOAA's National Centers for Environmental Information (NCEI) through the Climate Data Online (CDO) portal. Monthly average temperature observations were grouped by year to calculate annual average temperature. A linear regression was then used to estimate the long-term trend in annual temperature.

### Annual Temperature Trends

<img src="img/ptc_temp_trend.png" width="600">

**Figure 1. Annual average temperature in Peachtree City, Georgia.**

The annual temperature record shows year-to-year variability, but the overall trend is an increase in annual temperature. 
The linear regression indicates a change of approximately 0.06 degrees Celsius per year over the period analyzed. 

### Context

This site is located in an area where there has been minimal change in immediate surroundings as it is located at an airport and is the station used for the regional NWS office. While the period of record is short for most stations, this consistency of the site shows this increase in temperature over the last three decades is meaningful. However, there is one factor I believe should be considered for this site. As displayed by the graph above, average yearly temperatures were almost always below 17 Celsius prior to the mid-2010s. Starting in the mid-2010s, average yearly temperatures have all been right around or above 17 Celsius. This is significant because Lake Mcintosh, a 650 acres reservoir, reached full pool in the summer of 2013. Lake McIntosh is located immediately adjacent to the airport to the northwest, which is significant in proximity and also the fact that prevailing winds in this region are from the west and northwest. Winds typically are strongest in the fall through spring, which may lead to moderating temperatures locally especially during the cooler months of the year. Regardless, this station would likely show an overall increasing trend in temperature, but it could also be influenced by local changes.

<img src="img/ffc_lakemac.png" width="600">

**Figure 2. Lake Mcintosh proximity to airport.**

### Conclusion

Overall, the Peachtree City climate record shows an increase in temperature. However, this station may be biased post-mid-2010s due to changes in local geography with the introduction of Lake Mcintosh. A noticeable jump in temperature right after the reservoir filled gives reason to believe it may be influencing this site. I think it would be important to gather data from other stations in the area and compare to see if they had a similar jump in temperature around the same time in order to make a full conclusion about temperature trends in the area.

## American White Pelican Migration

## Species and Overview

American White Pelicans are one of the largest birds in North America. They spend their winters along the Gulf Coast, Mexico, Baja California, and California. When the weather warms, they migrate north to their nesting areas which include broad swaths of the Great Basin and the Great Plains, within the northern United States and into Canada (U.S. Army Corps of Engineers, St. Louis District, n.d.). This project displays the geographic distribution of American White Pelican occurrence records using an interactive map. The visualization uses georeferenced observations to explore spatial patterns across the species' range and examine how its distribution relates to seasonal migration.

## Interactive Map

<embed type="text/html" src="img/pelicans6.html" width="600" height="600">

The map displays American White Pelican occurrence records alongside ecoregion boundaries to provide geographic and ecological context.

## Data Sources

GBIF occurrence records provide georeferenced observations of the species. These records document reported locations rather than representing a complete census of the population. However, GBIF occurrence records are opportunistic observations and may be unevenly distributed. The map illustrates documented occurrences, not continuous migration routes or population abundance. Confirming seasonal migration patterns would require examining observation dates and comparing them with established research on the species.

## Methods

Occurrence records were retrieved from GBIF and processed using Python. Geographic data was prepared and combined with the occurrence records to produce visualization. The resulting map displays observations in their geographic context alongside ecoregion boundaries.

## Key Observations

- **Geographic distribution:** [Describe the major concentrations and broad distribution visible on the map.]
- **Migration patterns:** [Describe any apparent north–south or seasonal patterns supported by the records.]
- **Ecoregion context:** [Note any visible geographic patterns relative to the ecoregion boundaries.]

These patterns provide a starting point for exploring the species' distribution and migration. However, occurrence density can reflect observer effort and data availability as well as the species' actual distribution.

## Limitations

GBIF occurrence records are opportunistic observations and may be unevenly distributed across space and time. The map illustrates documented occurrences, not continuous migration routes or population abundance. Confirming seasonal migration patterns would require examining observation dates and comparing them with established research on the species.

## References

GBIF.org. ([Year accessed]). *GBIF occurrence download for American White Pelican (*Pelecanus erythrorhynchos*).* [Insert your specific GBIF download DOI or link.]

U.S. Army Corps of Engineers, St. Louis District. (n.d.). Pelican migration sheet [PDF]. https://www.mvs.usace.army.mil/Portals/54/docs/recreation/rivers/Birds/Pelican%20Migration%20Sheet.pdf



