# Citi-Bike-Challenge 

## Background 
This Tableau project analyzes Citi Bike trip data collected from June 2021 to May 2022. The analysis was designed to identify and visually communicate two key, unexpected phenomena found in New York City's shared mobility trends. Using multiple dashboards and geospatial mapping, this project highlights rider behavior differences between user types and reveals seasonal ridership patterns that could inform infrastructure and operational decisions. The visualizations are designed to inform urban planners, transit analysts, or anyone interested in shared mobility patterns.

Tableau Public: [Citi Bike Tableau Story](https://public.tableau.com/app/profile/madison.mihle/viz/citiBikeDataAnalysisJune2021-May2022/Story1?publish=yes)

## Objectioves & Criteria Met 
This project fulfills the assignment criteria by:
1. Aggregating Citi Bike Trip History Log data over a one-year period.
2. Identifying two unexpected phenomena and supporting each with 4+ visualizations.
3. Creating separate dashboards to explain each phenomenon.
4. Including a static map of NYC stations showing trip density.
5. Designing a professional Tableau Story presentation that incorporates all findings and trends.

## Methods:
* Aggregated trip-level data.
* Created calculated fields for trip duration and day-of-week.
* Extracted datetime values (seasons).
* Filtered and grouped stations by location. 

## Challenge 
#### PHENOMENON 1: Unusual Rider Behavior by Metics
This phenomenon explores how casual riders and members use Citi Bikes in significantly different ways, especially in terms of trip length, usage days, and behavior patterns.

**Visualizations Supporting This Phenomenon**:
* Average Member Type (Casual vs Member): Shows that casual riders take longer trips (~36 minutes), while members average ~16 minutes.
* Trip Duration of Recorded Riders: Binned histogram showing casual riders dominate longer-duration rides.
* Weekly Bike Usage by Member Type: Illustrates how casual riders prefer weekends and longer trips, while members use bikes consistently across the week.
* Ridership by Day of Week & Average Trip Duration by Day: Members dominate weekday commuting hours; casual riders increase on weekends.

**Insight**: Casual riders likely use bikes for exploration, while members use them for quick commutes. These insights can help tailor pricing models or marketing strategies.

**Results**

![Alt Text](https://github.com/maddieemihle/Citi-Bike-Data/blob/main/Images/Member%20Usage%3AType.jpg)

![Alt Text](https://github.com/maddieemihle/Citi-Bike-Data/blob/main/Images/Weekend%3AWeekday%20Usage.jpg)

#### PHENOMENON 2: Station-Specific Trends
This phenomenon identifies how ridership volume and patterns shift depending on the season, affecting demand across different stations.

**Visualizations Supporting This Phenomenon**:
* Seasonal Usage Rank of Bikes: Summer consistently has the highest usage; winter the lowest.
* Percent Change in Monthly Trips: Clear peak in summer/fall and steady decline in winter months.
* Popular Start & End Station Maps: Spatial distribution showing seasonally favored locations, e.g., near parks or offices.
* Top/Bottom 10 Stations: Stations with high/low traffic, likely influenced by weather, infrastructure access, or seasonal events.

**Insight**: These findings suggest bike redistribution should shift with the seasons, with more bikes placed in popular summer locations and commuter-heavy winter hubs.

**Results**

![Alt Text](https://github.com/maddieemihle/Citi-Bike-Data/blob/main/Images/Stations.jpg)

![Alt Text](https://github.com/maddieemihle/Citi-Bike-Data/blob/main/Images/Seasonal%20Usage.jpg)

#### Map Visualization
**Mapping Mobility**: Station Usage Across NYC:
* A static map shows station popularity using proportional bubbles for start and end locations.
* Visual patterns reveal commuter corridors and tourist-dense areas.

**Trend Noticed**: Start stations are often located near residential or transport hubs; end stations near commercial areas. This directional flow pattern emphasizes commuting behavior.

**Results**

![Alt Text](https://github.com/maddieemihle/Citi-Bike-Data/blob/main/Images/Map.png)

## Suggested Improvements/Future Work
* Incorporate additional demographic data (age, gender) to enrich behavior analysis.
* Develop a dynamic map for advanced temporal visualization.
* Add weather data to better correlate usage trends.
* Resolve limitations related to hourly data (future: better timestamp formatting before upload).

## Software Used 
* Tableau Desktop
* Tableau Public 
* Visual Studio Code 

## Resources: 
All trip data used in this project was sourced from the official Citi Bike System Data archive: https://s3.amazonaws.com/tripdata/index.html
