# Reddit Wine Project
A data analysis project from start to finish: collecting data using Reddit's API, analyzing the data using the Pandas library, and visualizing insights using Tableau.

The goal of this project is to see which wines are most popular in Reddit's r/Wine subreddit. We can then use that information along with wine flavor profiles from Winefolly to see which flavors are most popular in this subreddit.

To do this, I first used the Reddit API to download the top 1000 from the r/Wine subreddit. Next, I searched through the text of each post for mentions of common wines and counted the total number of times each wine was mentioned in the data. I used excel to create a data set of flavor profiles that correlate to popular wines using data from Winefolly, and then multiplied the values of each flavor based on the total number of mentions of that specific wine. Lastly, I created a visualization using Tableau from this data. 

Here is a link to the final visual dashboard: https://public.tableau.com/app/profile/ron.l2728/viz/RedditWineProject/Dashboard1

To read the project, start with the DataCollection jupyter notebook and then move onto the DataAnalysis notebook.
