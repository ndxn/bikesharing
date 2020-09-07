# Pedal Des Moines

Recent observations of the robustness of New York City's Citibank-sponsored bike share program, Citibike, have led to increased interest in deploying similar programs. Already, several other major cities, such as Chicago, Atlanta, and Austin, have seen the successful deployment of various bike share models.

The question is: can the success of such a system be reasonably guaranteed in Des Moines?

We think so becase Des Moines is Des Best!

## The Analysis
Deciding on whether a transportation model can be plucked from one metropolitan area and **successfully** implemented elsewhere requires taking in and processing data pertaining to many key factors including population demographics, density, industry, and weather. This first phase of the analysis focuses primarily on age and income demographics.

The following subsections dive into the data as presented in the Tableau story. Data sources will be cited. All uncited data comes directly from Citibike.

### Age and Gender Trends

Everyone loves a bike ride but not everyone loves them enough to actually go on one. Different age groups will have different modal preferences so it's important to consider who gets around by bike. This triptych of horizontal bar graphs compares identically summarized data for the population of Citibike riders, New York City as a whole, and Des Moines. The findings here are telling: all three metrics see the largest representative groups as 25 to 29 years followed by 30 to 34 years. It should be noted that all three metrics compare represetnative portions expressed as percents instead of the actual values. Des Moines is obviously a smaller city. The question isn't whether a smaller city can support a bike share program--after all, the fleet will be sized accordinglty. The question is whether Des Moines has the trends to support a bike share program. The similarities in the aggregate data would suggest that Des Moines might have a population that would be willing to take part in a bike share scheme.

Another dimention has been incorporated into the data and that is a gender breakdown. The color of the bars shows the balance of genders in each population group. The correslation between gender and shared bike use in NYC is marked but it is unlikely that the breakdown within a city would be deterministic of the success of a shared bike program.

It should be noted that the summarizing the Citibike ride data was a multi-step process. With more than 2.3 million records, it was necessary for the original summarization by birth year/age to be done within Tableau. The summarized data was exported to CSV. Outliers were removed and new values interpolated as necessary. Finally, the data was summarized into the same bins as used in the American Community Survey. 

Source: New York and Des Moines dempgraphc data is from the 2018 American Community Survey 5-year estimates.

### New York and Des Moines Median Ages with an Overlay of Ride Start Station Data

The purpose of this story point is to show some dimension about the spatial distirbtion of the population by age. The data for the ride start station has been included for the purposes of visual analysis. The charts on this story point use map later population data, as it seems Tableau charts are limited to data that can be connected with joins. As the station data does not correlate with Census geographies, it seems it is not possible to have both spatial data for the stations and for the Census shape files.

The takeaway from this data seems limited. The idea median age would fall just under the 33.2 break in the map layer legend. Still, median data does not speak to the represenative portion that the particular group would have. It would seem from the visualization that New York has a more even age distribution, with various median ages being represented throughout the city, whereas Des Moines appears to have an older periphery.

Source: Base Maps are layers provided within Tableau without citation of their original sources.

### New York and Des Moines Mean Income

Mean income, especially at the Census Tract level, can speak volumes about a community. The data itself usually is comprised of enough points that the mean income, relative to the rest of the area, will be idicative of the income levels. In this side-by-side comparison, it can be seen that New York and Des Moines have a surprising trend. Des Moines, for the most part, follows the typical trends of American cities, where households on the periphery of a city tend to be slightly better off financially. New York, however, has much of the weatlth concentrated in the center. 

The disparity in the trends does not necessarily spell doom for the program in Des Moines. There could be many reasons for the correlation between higher wealth and higher bike usage including population and business density or tourism. That being the case, it will be important for Des Moines planners to understand well the demand that will be expected.

Souces: Shapefiles are from the US Census, 2017 TIGER/Line® Shapefiles: Census Tracts. Demopgraphic data comes from datausa.io and is based on the 2017 ACH data.

### Weather

Let's not kid ourselves. As important as information about the population is for determing if there is a viable need, weather--especally when we're dealing with the Midwest and the Northeast--is a critical concern. This page compares the average high and low temperatures by month as well as the monthly number of days with precipitation. While New York has the reputation of being rather cold, at least for a large city, winter temperatures may have a greater effect on cycling in Des Moines.

Source: Weather data comes from NOAA.

## The Tab
And, now, for the moment you've been waiting for... [the Pedal Des Moines Tableau story!](https://public.tableau.com/profile/neal1574#!/vizhome/Bikedata_15994605528710/PedalDesMoinesTheCaseforaLocalBikeShare?publish=yes)
