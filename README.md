# NBA Player Bio and Season Statistics - ETL Challenge

## Project Proposal

There is a short supply of finding a historical database of every single NBA Player's season statistics that also contain some of their biographical information. When trying to find one, they are usually separated, till now. My project goes back to the first season the NBA started charting game statistics and biographical information. With these resources I hope to provide a resource which any fan of the NBA can use to chart innumerous amounts of analyses.

The NBA Player Biographical Table lists imporant information like name, height in centimeters, weight in pounds, college they graduated from, and year they were born.

The NBA Player Season Statistics Table is longer, hosting 31 columns, it details every single season the players had appeared in with how many points, rebounds, assists, steals, turnovers, shooting efficiency and percentage, and so much more!

I hope you enjoy the product of my hard work and hope you're able to utilize it and build it even further. 

## Finding Data

I utilized data from three sites:

* [NBA.com](https://www.nba.com/stats/)
This website confirmed if the below information was credible to use.

* [Kaggle](https://www.kaggle.com/drgilermo/nba-players-stats)
This website provided detailed season statistics for each NBA Player.

* [Kaggle](https://www.kaggle.com/justinas/nba-players-data)
This website provided detailed biographical information for each NBA Player.

## Data Cleanup & Analysis

Once you have identified your datasets, perform ETL on the data. Make sure to plan and document the following:

* The sources of data that you will extract from.

* The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc).

* The type of final production database to load the data into (relational or non-relational).

* The final tables or collections that will be used in the production database.

You will be required to submit a final technical report with the above information and steps required to reproduce your ETL process.

## Project Report

At the end of the week, your team will submit a Final Report that describes the following:

* **E**xtract: I extracted the data from these websites and was able to ensure that they were uniformly formatted as csv files.

* **T**ransform: The data had to be cleaned up thoroughly. Information like draft round number and usage rate would clump up the data sets. I wanted to ensure that the data was cleaned to be understood by an average NBA fan, not for the very few who enjoy advanced statistics. Though that will be something I include in the near future as a fun project.

* **L**oad: I loaded the final database and was able to pull the two tables, NBA Player Bios and NBA Player Season Statistics, using pgAdmin 4. 


Enjoy and I hope you find all of these wonderful resources useful!


- - -

### Copyright

Coding Boot Camp © 2019. All Rights Reserved.
