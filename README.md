# NBA Player Bio and Season Statistics - ETL Challenge

## Project Proposal

There is a short supply of finding a historical database of every single NBA Player's season statistics that also contain some of their biographical information. When trying to find one, they are usually separated, till now. My project goes back to the first season the NBA started charting game statistics and biographical information. With these resources I hope to provide a resource which any fan of the NBA can use to chart innumerous amounts of analyses.

The NBA Player Biographical Table lists imporant information like name, height in centimeters, weight in pounds, college they graduated from, and year they were born.

The NBA Player Season Statistics Table is longer, hosting 31 columns and almost 25,000 rows! It details every single season the players had appeared in with how many points they scored, and also their rebounds, assists, steals, turnovers, shooting efficiency and percentage, and so much more!

I hope you enjoy the product of my hard work and hope you're able to utilize it and build it even further. 

## Finding Data

I utilized data from three sites:

* [NBA.com](https://www.nba.com/stats/)
This website confirmed if the below information was credible to use.

* [Kaggle](https://www.kaggle.com/drgilermo/nba-players-stats)
This website provided detailed season statistics for each NBA Player.

* [Kaggle](https://www.kaggle.com/justinas/nba-players-data)
This website provided detailed biographical information for each NBA Player.

## Project Report

At the end of the week, your team will submit a Final Report that describes the following:

* **E**xtract: I extracted the data from the above websites and was able to ensure that they were uniformly formatted as csv files. Ensuring that they were correct took a long time but was worth the effort. 

* **T**ransform: The data had to be cleaned up thoroughly. Information like draft round number and usage rate would clump up the data sets. I wanted to ensure that the data was cleaned to be understood by an average NBA fan, not for the very few who enjoy advanced statistics. Though that will be something I include in the near future as a fun project! Also, some NBA statistics weren't accounted for till later on. For example, Player Efficiency Rating sums up all a player's positive accomplishments, subtracts the negative accomplishments, and returns a per-minute rating of a player's performance but this statistic can't actually be calculated till blocked shots and steals were officially recorded in the 1973-1974 NBA season. As such, I didn't want a player who didn't have this statistic due to unrecorded numbers in previous seasons to show up as "0". It was an easy adjustment to ensure that that cell in the corresponding row and column was listed as "N/A". 

* **L**oad: I loaded the final tables to a relational database, utilizing names that would link each players' biographical information to their their seasonal statistics. Each player has often played a multitude of seasons in the NBA and as such, will have multiple appearances in the Statistical Table but one appearance on the Biographical Table. For example, Michael Jordan has played a total of 15 seasons. As such, he will have 15 rows in the Statistical Table but only appears once in the Biographical Table. I was able to pull the two tables, NBA Player Bios and NBA Player Season Statistics, using pgAdmin 4. 


Enjoy and I hope you find all of these wonderful resources useful!


- - -

### Copyright

Coding Boot Camp © 2019. All Rights Reserved.
