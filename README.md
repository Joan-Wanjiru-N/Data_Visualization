# (Ford GoBike Dataset Exploration)
## by (Joan Njeri)


## Ford GoBike Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The data includes information about 183,000 rides made in a bike-sharing system covering the greater San Francisco Bay area and 16 fetatures that includes 'duration_sec', 'start_time', 'end_time', 'start_station_id','start_station_name'and some additional variable

### Libraries used
> Numpy
> Pandas
> Seaborn
> matplotlib
### Data Wrangling 
#### Assessing and Cleaning
> Removed entries with missing values
> Converted the time column to DateTime and extracted the Year column
> Calculated the age for riders
> Converted duration (sec) to min
> Removed the outliers in age and duration min

#### Exploration 
> First univariate exploration using one variable at a time. Investigating the distibution of say duration_se and age.

> For Bivariate Exploration, I investigated trip gender vs user type, duration vs age, gender vs duation

> Multivariate Exploration, I investigated on the relationship between age, duration and gender.

## Summary of Findings
> This dataset in duration can be described by a uniform distribution, highest peak being at 10 minutes.
For Ford GoBike riders’ dataset the age distribution is more concentrated between 25 to 40 years old indicating that younger people are involved in riding trips. Customers take longer durations as compared to subscribers an assumption that a customer make full use of the day paid. Again, 74.61 percent of the bike riders are male and for which they are male subscribers.
we found that males take the highest percent in this dataset but roughly they take shorter durations compared to females and others.

## Key Insights for presentation
> For insights, myh main focus was on how age, gender, and if some have purchased a subcription affect bike riding. I started by calculating the ages for all the riders, then compared to duration in this case calculated in min for better understanding. Fair enough, younger riders (25-40) tend to have longer durations as compared to older riders (65-above).
It is expected that male dominant in bike riding and it is indeed confirmed, with most them having a Ford GoBike subsription as comapred to other and females, but we geta twist as females and other relatively take longer durations in bike riding.
