# 2015 Temperature Data Visualization And Comparaison

In this notebook we will be looking at the tempature variation between the years 2005 and 2014, then we will doing a comparison with the year 2015's temperatures and see where the it surpasses that period's record **low** or **high** temperatures.

An NOAA dataset has been stored in the file `Data/BinnedCsvs_d400/fb441e62df2d58994928907a91895ec62c2c42e6cd075c2700843b89.csv`. The data comes from a subset of The National Centers for Environmental Information (NCEI) [Daily Global Historical Climatology Network](https://www1.ncdc.noaa.gov/pub/data/ghcn/daily/readme.txt) (GHCN-Daily). The GHCN-Daily is comprised of daily climate records from thousands of land surface stations across the globe.

Each row in the datafile corresponds to a single observation.

It contains the following variables :

* **id** : station identification code
* **date** : date in YYYY-MM-DD format (e.g. 2012-01-24 = January 24, 2012)
* **element** : indicator of element type
    * TMAX : Maximum temperature (tenths of degrees C)
    * TMIN : Minimum temperature (tenths of degrees C)
* **value** : data value for element (tenths of degrees C)

We will :

1. Write some python code which returns a line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day will be shaded.
2. Overlay a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.
3. Watch out for leap days (i.e. February 29th), it is reasonable to remove these points from the dataset for the purpose of this visualization.
4. Make sure that the visual effectively leverages the guidelines given for effective visual design (e.g., beauty, truthfulness, functionality, and insightfulness).

The data contains temperature information for **Ann Arbor, Michigan, United States**, and the stations the data comes from are shown on the map below.

![Temperature stations in Ann Arbor, Michigan, United States](/Map.png)
Format: ![Temperature in Ann Arbor, Michigan, United States](url)

And final graph is shown below :
![2015's temperature breaking points against 2005-2014 in Ann Arbor, Michigan, US](/Temp_Plot.png)
Format: ![2015 vs 2005-2014](url)

