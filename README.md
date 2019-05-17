# Bluebikes
This project uses data from Blue Bikes (https://www.bluebikes.com/system-data), the bike sharing program in Boston. The website contains all trip histories for customers over all time. We found that there is a significant population who were born in 1969 and with a nonbinary gender.
![birth_years](data/birth_years.png?raw=true "Title")

**The question we choose to investigate was...**
What does the commute and activity of users, that were born in 1969 and chose "Other" as their gender, look like? What are some popular start/end stations?
Why could they be so popular?
How does the popularity of those stations change depending on weekdays? What about weekends?

**What we did**

We cleaned the data and used univariate and bivariate analysis, examined and ploted pivot tables and interesting aggregates. We then investigated the likely missingness mechanisms of our data as being missing at random, perform permutation tests to analyze the dependency of the missingness of a specific column on other columns. Lastly, we formulated a null hypothesis and perform a hypothesis test that explicitly stated the (null and alternative) hypothesis, the test-statistic, the significance level, the resulting p-value and results.
![all_stations](data/all_stations.png?raw=true "Title")

## Installation
Clone this repo.
```bash
git clone https://github.com/ppengster/Bluebikes.git
cd Bluebikes/
```

This code requires Folium and Shapely. (You may experience problem installing Shapely on Windows)
```
pip install Folium, Shapely
```

It is important for you to have the geojson files in the data folder.
