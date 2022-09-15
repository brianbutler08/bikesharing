# Bikesharing

# Overview

For this project, we conducted various analyses of a dataset from the Citi Bike bikesharing program in New York City from August, 2019. The overall goal was to draw some conclusions from the analysis in order to provide guidance to another city interested in starting a bikeshare program. The dataset included the following fields for each bike trip taken during the month:
- Trip duration
- Trip start and end times
- Name and ID of the starting and ending bike stations
- Latitude and longitude of the starting and ending bike stations
- ID of each bike
- Type of user (subscriber or customer)
- Birth year and gender of the rider

# Results

The most important visualizations were compiled into a Tableau Story, which can be found here: [link to dashboard](https://public.tableau.com/app/profile/brian.butler1174/viz/Challenge_16625093032150/NYCCitiBikeStory)

The first page includes an overall look at some key data, including the total number of riders and a breakdown by gender and user type. Additionally, I mapped the starting and finishing locations of each bike rental, using size and color to modify each marker to indicate the relative number of trips.

!["1"](https://github.com/brianbutler08/bikesharing/blob/main/Images_bikesharing/1.png)

Next, we wanted to look at the duration of each trip and how that may differ by gender. Overall, the most common trips were between 4 and 6 hours, with longer trip durations tending to taper off in frequency. The trend shown by male riders mirrored that of the whole dataset, while the results for female riders was similar, albeit with less of a peak around the five hour mark.

!["2"](https://github.com/brianbutler08/bikesharing/blob/main/Images_bikesharing/2.png)

An important step in this analysis was to visualize bike usage by hour for each day of the week. Between Monday and Friday, there are clearly two times of high usage - around 8:00 AM and between 5:00 and 7:00 PM. These time ranges correspond to daily commuting times, suggesting that many of the riders in this program are using Citi bikes to get to work and return home again. Weekend patterns are distinctly different, with the highest usage happening between the late morning and late afternoon, suggesting more recreational usage.

!["3"](https://github.com/brianbutler08/bikesharing/blob/main/Images_bikesharing/3.png)

When we look at this same dataset divided by gender, the pattern remains (although males are riding at two to three times the levels of females during each time block). Looking at trips by user type (and gender) provides support to our earlier theory, that subscribers are using the bike program primarily during weekdays and customers ride more often on the weekend.

!["4"](https://github.com/brianbutler08/bikesharing/blob/main/Images_bikesharing/4.png)

# Summary

A dataset as large as the one utilized here lends itself to a significant number of possible visualizations and analyses. The work above focuses on looking at the data through a gender perspective, but I created two additional visualiztions involving the types of user - subscribers and regular customers. I wanted to see if there was a difference in the stations that each used to start or stop their journey, assuming that customers might likely be tourists and subscribers would be residents and work commuters.

!["5"](https://github.com/brianbutler08/bikesharing/blob/main/Images_bikesharing/5.png)

Looking at the map of customer starting locations, there appears to a higher number of starts around Central Park and close to the Hudson River. The second visualization helps to clarify this idea and looks specifically at the top ten most used starting locations. While subscribers use the Citi Bike program in much larger numbers than customers, the top three locations used by customers were relatively less used by subscribers, ranked 8th, 9th and 10th. 

Furthermore, the top three customer start locations can be found near parks, shopping and tourist attractions:
- 12th Ave and 40th St - next to the Hudson River at the ferry terminal and near museums
- Broadway and W 60th - Columbus Circle, at the edge of Central Park and a large shopping mall
- West St and Chambers St - Rockafeller Park, near Battery Park sports fields and Tribeca
