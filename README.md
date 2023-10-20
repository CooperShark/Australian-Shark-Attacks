# Australian-Shark-Attacks

## Topic:
## Influences of environmental variables on Australian shark behavior.

## Work Flow:
Download Shark Attack `csv` queried from Australian Shark Incident Database into Jupyter Notebooks.
Import _cartopy_, _numpy_, _matplotlib_, and _geopandas_, using Python to plot shark attack locations categorized by shark species. Plot the points over an Australian Coastline map.

1. Download Ereefs AIMS environmental variable dataset for sea surface temperature, salinity, and chlorophyll-a.
2. Temporal scale: Monthly rate of change from 2010-2019.
3. Spatial Scale: Latitude: -28.7,-28.67,-7.066,-7.036 Longitude: 142.2,142.2,156.8,156.9

Only shark attacks that fall within these spatial parameters will be included in the QLD casestudy (n=61).
Each Ereefs environemtal variable was sliced from the top 3 meters of ocean surface. We then calculated mean averages from each year and across the average 10 year period to calculate mean variable change.
Next, we overlayed corresponding shark attack coordinates with changes in enrionemental variables of the same locaations. We then correlated change in environmental varaiables with shark attack frequency, by categorizing frequency of shark attacks by High and Low years. High years indicated annual shark attacks > 30, and low shark attack years represented annual shark attacks < 15. 

Subsequently, we analyzed different site categories (Coastal, Island/Open Ocean, River) to isolate potential activity hot spots, and to better understand how separate environments could also influence variable and behavioral change.
In doing so, we found that rivers heavily influence chlorophyll-a change, which had a negative -.51 correlation coefficient with shark attack frequency. We discovered this by creating a correlation coefficient heat map - representing the statistical influence that environmental change has on shark attack frequency.  

> Finally, we investigated proportion of bites and fatality rates for the three most dangerous sharks (Bull, Tiger, White) by creating a stacked bar graph. This was an attempt to highlight attack severity, and to better understand whether different shark species have bahvioral and/or hunting preferences. 
