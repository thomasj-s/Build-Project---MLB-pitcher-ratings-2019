 <h1>Starting Pitcher Gamescore insights - 2019 season.</br></h1>
 
**A look at MLB 2019 average gamescore pitcher ratings per team and impact.**

<h2>Cleaning</h2>
This project starts with some data cleaning from a dataset that contains individual games as rows, with the away and home pitcher's current gamescore as features.  The cleaning 
process consists of dropping unnecessary features, feature engineering, and re-structuring for our needs.

</br>**Feature engineering**</br>
The features we needed to engineer were wins and losses per team, per year for the revious 8 years.  This was possible as the final run count of each game was a given feature, in
addition to abbreviations for the teams involved.  We also engineered an average pitcher rating per team, per year for previous 8 years.  This gave us a picture of a teams recent 
seasons win/loss rate in congruence with average pitcher rating for the year.  

<h2>Re-evaluate scope of project</h2>
Our goal was to viaualize 8 years of data, but I was not capable of creating this visualization at the time of the project.  This will be revisited in the future. I changed scope 
after realizing my initial goal of 8 years of data would not be easy for me to visualize in a coherent way.  I decided to instead, take a look at the most previous season for a 
correlation between playoff teams and pitcher rating.  The assumption might be that certain teams might make the playoffs with the help of offensive stats, and have an average 
(50) or below average pitcher rating.

<h2>Results</h2>
The results showed that a few things.  Most notably are as follows; There was an obvious association between pitcher rating and win pct, that there is a clear distinction that only 
teams with an above average pitcher rating finish with over a 50% win pct, and that the two world series teams for that year also were the teams with the two highest gaemescore.
