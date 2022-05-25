# Understanding Guitar Tablature and Popularity

#####Introduction:
#####Objective:
The objective of this project is to learn what makes guitar tablature popular in relation to attributes of the song and the portrayal of the guitar tablature itself. After learning what makes a tablature popular, we will go back through the data and make actionable recommendations on what other songs would, based on our findings, gain reasonable traction on the website ultimate-guitar.com.

#####Data Description:
The datasets we will be using are both open-source datasets pulled from Kaggle.com. The first is a dataset pulled from the top 850 tablatures on ultimate-guitar.com. This data can be found here The other dataset I will be using is also from Kaggle, but was originally pulled from Spotify APIs. It contains metadata revealing details about 440,000 of the top songs. This data can be found here

#####Limitations:
Some limitations of this dataset are as follows:

-There are no unique IDs for each tablature that corresponds to a unique idea to the Spotify Data. This means that the data is not easily joinable, and some rows will simply be unable to be joined.
-The Guitar Tabs data is from 2019, while the Spotify data is newer. Thus, the Guitar Tabs data may not reflect the reality of ultimate-guitar.com perfectly for 2022.
-This analysis uses only metadata about the music and the tablature itself. There is no measure for quality of the tablature in our data and there is no user data about the guitar players that use ultimate-guitar.com. These factors could be a large player in how popular tablature can become, but we have no way to measure this.
