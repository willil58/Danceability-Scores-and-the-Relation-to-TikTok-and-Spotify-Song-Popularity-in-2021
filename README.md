# I310-Assignment-1
I was curious how danceability scores affected how popular a song was on Spotify and TikTok and wanted to visually see how the popularity scores related to danceability on each application. I felt the best way to do this was to create a line graph.

For this project, I sourced two data sets on Kaggle about popular TikTok and Spotify songs in 2021. I was interested in examining the relationship between a song’s popularity on each app and its danceability score. To do this I made a data frame and for both TikTok and Spotify containing only the popularity and danceability scores and ordered them by danceability scores. I then made a separate for both TikTok and Spotify line graph with popularity scores on the y axis and danceability scores on the x axis. Next, I combined the two data frames I created and made a line chart with both TikTok and Spotify popularity scores on the y axis and danceability scores on the x axis. This allowed me to compare how danceability relates to popularity scores. I found that for both TikTok and Spotify the danceability score doesn’t appear to impact a song’s popularity.


I found the data set TikTok popular songs 2021 on the following link: https://www.kaggle.com/datasets/sveta151/tiktok-popular-songs-2021?resource=download
This data set is licensed under CC0 1.0 Universal (CC0 1.0) Public Domain Dedication

I found the data set Spotify top 50 songs in 2021 on the following link: https://www.kaggle.com/datasets/equinxx/spotify-top-50-songs-in-2021
This data set is licensed under CC0 1.0 Universal (CC0 1.0) Public Domain Dedication

The data set I created is licensed under CC0 1.0 Universal (CC0 1.0) Public Domain Dedication

Data Dictionary 

Attribute	- Data Type	- Description

danceability - int - This is the score for how easy it is to dance to the song on a scale of 0-1

tiktok popularity	- int -	This is the score for how popular a song is on TikTok in 2021 on a scale of 0-100

spotify popularity- int	- This is the score for how popular a song is on Potify in 2021 on a scale of 0-100


Limitations: The data found for TikTok was on publicly open site and didn’t say whether or not TikTok themselves provided the raw data or how the data was collected. The raw data didn’t explain how danceability was calculated so it’s possible that different data sources could score danceability differently. It's important to note that this data is from 2021 and the popularity scores of songs will be different prior to and after 2021.
