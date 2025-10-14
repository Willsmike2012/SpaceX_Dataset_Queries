# SpaceX_Dataset_Queries
SpaceX has gained worldwide attention for a series of historic milestones.
SpaceX is the only private company ever to return a spacecraft from low-earth orbit, which it first accomplished in December 2010. It advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars whereas other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage.
Therefore if we can determine if the first stage will land, we can determine the cost of a launch.

This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

This dataset includes a record for each payload carried during a SpaceX mission into outer space.
## Objectives
Using this Python notebook to perform these tasks, I will:

1.  Understand the Spacex DataSet
2.  Load the dataset  into the corresponding table in a Db2 database
3.  Execute SQL queries to answer questions concerning various tasks including:
   - Display the names of the unique launch sites  in the space mission
   - Display 5 records where launch sites begin with the string 'CCA'
   - Display the total payload mass carried by boosters launched by NASA (CRS)
   - Display average payload mass carried by booster version F9 v1.1
   - List the date when the first succesful landing outcome in ground pad was acheived.
   - List the names of the boosters which have success in drone ship and have payload mass greater than 4000 but less than 6000
   - List the total number of successful and failure mission outcomes
   - List all the booster_versions that have carried the maximum payload mass. Use a subquery.
   - List the records which will display the month names, failure landing_outcomes in drone ship ,booster versions, launch_site for the months in year 2015.
   - Rank the count of landing outcomes (such as Failure (drone ship) or Success (ground pad)) between the date 2010-06-04 and 2017-03-20, in descending order.
     

# **Launch Sites Locations Analysis with Folium**
In the previous exploratory data analysis labs, I have visualized the SpaceX launch dataset using `matplotlib` and `seaborn` and discovered some preliminary correlations between the launch site and success rates. In this lab, I will be performing more interactive visual analytics using `Folium`.
## Objectives
This lab contains the following tasks:
- **TASK 1:** Mark all launch sites on a map
- **TASK 2:** Mark the success/failed launches for each site on the map
- **TASK 3:** Calculate the distances between a launch site to its proximities

After completing the above tasks, I was able to find some geographical patterns about launch sites.
