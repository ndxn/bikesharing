# Pedal Des Moines

Recent observations of the robustness of New York City's Citibank-sponsored bike share program, Citibike, have led to increased interest in deploying similar programs. Already, several other major cities, such as Chicago, Atlanta, and Austin, have seen the successful deployment of various bike share models.

The question is: can the success of such a system be reasonably guaranteed in Des Moines?

We think so becase Des Moines is Des Best!

## The Analysis
Deciding on whether a transportation model can be plucked from one metropolitan area and **successfully** implemented elsewhere requires taking in and processing data pertaining to many key factors including population demographics, density, industry, and weather. This first phase of the analysis focuses primarily on age and income demographics.

The following subsections dive into the data as presented in the Tableau story. Data sources will be cited. All uncited data comes directly from Citibike.

### Age Trends

Everyone loves a bike ride but not everyone loves them enough to actually go on one. Different age groups will have different modal preferences so it's important to consider who gets around by bike. This triptych of horizontal bar graphs compares identically summarized data for the population of Citibike riders, New York City as a whole, and Des Moines. The findings here are telling: all three metrics see the largest representative groups as 25 to 29 years followed by 30 to 34 years. It should be noted that all three metrics compare represetnative portions expressed as percents instead of the actual values. Des Moines is obviously a smaller city. The question isn't whether a smaller city can support a bike share program--after all, the fleet will be sized accordinglty. The question is whether Des Moines has the trends to support a bike share program.

It should be noted that the summarizing the Citibike ride data was a multi-step process. With more than 2.3 million records, it was necessary for the original summarization by birth year/age to be done within Tableau. The summarized data was exported to CSV. Outliers were removed and new values interpolated as necessary. Finally, the data was summarized into the same bins as used in the American Community Survey. 

Source: New York and Des Moines dempgraphc data is from the 2018 American Community Survey 5-year estimates.

### New York and Des Moines Median Ages



Source: Base Maps are layers provided within Tableau without citation of their original sources.

### New York and Des Moines Mean Income

Souces: Shapefiles are from the US Census, 2017 TIGER/Line® Shapefiles: Census Tracts. Demopgraphic data comes from datausa.io

## The Tab
And, now, for the moment you've been waiting for... [the Pedal Des Moines Tableau story!](LINK GOES HERE)
