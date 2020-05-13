# Insights into COVID-19 Critical Trends through Bubble Maps and Choropleth Maps


## Background
In light of the ongoing Coronavirus pandemic that has since altered our daily lives, the Johns Hopkins University has been conscientiously updating their COVID19 data analyses to aid in the fight against COVID-19. As of April 26th, the U.S. has reached the stage where identifying coronavirus hospots, peaks, and epicenters is crucial. For some counties and states that have either not been too affected by the coronavirus, or have already peaked in the number of coronavirus cases and deaths, a reopening phase may be a potential consideration, and for other states like New York which still remain largely affected, a reopening phase may need to be delayed. In order to implement any policies, future guidelines, or steps, we need to better understand the location of active cases and the confirmed cases and death reports by county. The U.S. is dealing with lives here, and it is important that we fully analyze and understand coronavirus trends with the understand that these analyses can save lives.

## Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents? How can we use coronavirus data trend analyses to better implement future policies on reopening?

Our business question here remains twofold, as our main purpose of analyzing coronavirus trends is to understand the toll that coronavirus has placed on U.S. counties. However, we are reaching the stage where a reopening can be a possibility, at least in certain counties, so through our interactive heat map and map of COVID-19 cases, we can also attempt to answer how we can go about implementing policies by state/county moving forward.

## Data Question
We will be using data from the following sources:

- [JHU CSSE COVID-19 Case Data](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)
- [New York Times COVID-19 Data](https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv)
- [U.S. County Geospatial Data](https://raw.githubusercontent.com/plotly/datasets/master/geojson-counties-fips.json)


## Data Answer/Analysis


![Covid 19 Cases Bubble Map](https://github.com/drewshlee/COVID19-Critical-Trends-Geospatial-Data-Analysis/blob/master/COVID19%20cases%20bubble%20map.PNG)

In our first data visualization, the bubbles on the map, by size, represent the total number of confirmed COVID-19 cases. We can see that the largest bubbles are around the East coast of the United States, particularly in the tri-state area. We can attribute some of the high number of total COVID-19 cases to high population density in areas like NYC, and the amount of travel in and out of areas like New York City. Based on this bubble map, New York and New Jersey need to strictly impose social distancing guidelines and monitor the healthcare system (number of beds available, etc.) because of the sheer number of confirmed COVID-19 cases. Other East coast states should follow in a similar manner.


![Countries and Counties with Highest Total Confirmed Cases](https://github.com/drewshlee/COVID19-Critical-Trends-Geospatial-Data-Analysis/blob/master/Countries%20and%20Counties%20with%20Highest%20Total%20Confirmed%20Cases.PNG)

Wanting to take a look at more specific county/city level data, I created a bar chart of the areas, across the world, that have the highest total confirmed COVID-19 cases. Excluding some of the country level data shown, unsurprisingly, New York City and Nassau + Suffolk Counties (all of which are close to home) have some of the highest total confirmed cases of COVID-19. County and state leadership in New York can use this kind of data to A). try and convince the federal government that the U.S. needs more medical assistance, and B). that compared to other COUNTRIES, New York City and related counties have some of the highest confirmed cases of COVID-19, so everyone really needs to adhere to strict social distancing guidelines. These visualizations can be used as a persuasion tool to get people to understand that, at the time (looking back), New York and related counties were at greatest risk of suffering the extreme consequences of the COVID-19 pandemic. 


![Density Heatmap](https://github.com/drewshlee/COVID19-Critical-Trends-Geospatial-Data-Analysis/blob/master/Density%20Heatmap.PNG)


![Choropleth map](https://github.com/drewshlee/COVID19-Critical-Trends-Geospatial-Data-Analysis/blob/master/Choropleth%20Map.PNG)

And lastly, according to our last two data visualizations, Western states seem to have less confirmed COVID-19 Cases, and the highest number of confirmed COVID-19 cases seem to be in the NY, NJ, MA, MD states, which generally have a lot of "traffic" (people going in and out for work, etc.). It is critical that the state and county governments (as well as businesses) in these states enforce social distancing guidelines so that the rate of increase of the number of confirmed COVID-19 cases slows down. 


## Business Answer Interpretation
The data visualizations in question illustrate a rather stark contrast between Eastern and Western states: Aside from California, the number of confirmed COVID-19 cases in states like Montana and Utah are negligible (although these states should still enforce social distancing). These states may continue with possible reopening plans to stimulate their economies, while providing necessary medical PPE to Eastern States.

On the East coast, particularly in the Northeast where NY, NJ, and MA are located, social distancing is a PRIORITY. Local and State governments should use their power to obtain PPE and other necessities from other states in the U.S. that aren't as affected. 

However, it is difficult to make a conclusion. In the Eastern states, herd immunity may be a potential solution, with such a large number of total COVID-19 cases (also accounting for the number of COVID-19 cases that aren't accounted for because of lack of testing equipment). Perhaps these states should try to aim for herd immunity as a treatment/solution, while states in the West should be particularly wary of a resurgence in COVID-19 cases (or becoming the next epicenter). 

It is also difficult to draw conclusions here because I doubt this data is fully representative of the number of confirmed COVID-19 cases. Some state and local governments don't particularly care for testing and simply would like to reopen businesses, and other states don't have enough financial resources to obtain more testing kits. 

The COVID-19 pandemic has changed the scope and future of the world, and in these trying times, countries and states should work together. Each country/state's experience of the COVID-19 pandemic has been different, and it's up to people to follow social distancing guidelines, and the state/local/federal governments to protect its people by means of more testing, providing PPE, and more.
