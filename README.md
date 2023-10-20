# Australian-Shark-Attacks

## Topic:
## Influences of environmental variables on Australian shark behavior.

<div align="center">
  <img width="800" alt="OZShark" src="https://github.com/CooperShark/Australian-Shark-Attacks/assets/148509976/b8a69048-bcea-4ddf-b2f1-7c97b37fc7d9">
</div>

## Work Flow:
Download Shark Attack `csv` queried from Australian Shark Incident Database into Jupyter Notebooks.
Import _cartopy_, _numpy_, _matplotlib_, and _geopandas_, using Python to plot shark attack locations categorized by shark species. Plot the points over an Australian coastline map.

1. Download Ereefs AIMS environmental dataset for 3 different variables: sea surface temperature (sst), salinity, and chlorophyll-a.
2. Temporal scale: Monthly rate of change from 2010-2019.
3. Spatial Scale: Latitude: -28.7,-28.67,-7.066,-7.036 Longitude: 142.2,142.2,156.8,156.9

4. Only shark attacks that fall within these spatial parameters will be included in the QLD casestudy (n=61).
5. Each Ereefs environemtal variable was sliced from the top 3 meters of ocean surface. We then calculated mean averages for each year and across the 10 year period to calculate overall mean variable change.
6. Next, we extracted environmental variables with the corresponding locations of attack coordinates over the same 10 year period (2010-2019). We then correlated change in environmental varaiables with change in shark attack frequency by categorizing frequency of shark attacks by High and Low years. High years indicated annual attacks >30, and low shark attack years represented annual shark attacks <15.

 <div align="center">
<img width="800" alt="OZShark2" src="https://github.com/CooperShark/Australian-Shark-Attacks/assets/148509976/f1439a66-4e27-4259-ac60-8e100f6163d8">
</div>

7. Subsequently, we analyzed 3 different site categories (Coastal, Island/Open Ocean, River) to isolate potential activity hot spots, and to better understand how different ecosystems could also influence behavioral and variable change.
8. In doing so, we found that rivers heavily influence chlorophyll-a change, which had a negative -.51 correlation coefficient with shark attack frequency. We discovered this by creating a correlation coefficient heat map - representing the statistical influence that environmental change has on shark attack frequency.  

9. Finally, we investigated the proportion of bites and fatality rates for the three most dangerous shark species (Bull, Tiger, White) by creating a stacked bar graph. This was an attempt to highlight attack severity, and to better understand whether different shark species have bahvioral and/or hunting preferences. 

<div align="center">
<img width="500" alt="OzShark3" src="https://github.com/CooperShark/Australian-Shark-Attacks/assets/148509976/2640ea2e-7876-4c95-b5ee-89720d71cd79">
</div>
