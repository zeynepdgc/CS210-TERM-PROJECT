# Zeynep Dağcı DSA210-TERM-PROJECT 

# Motivation

The reason I chose to work on these datasets as my project topic is that Spotify and Netflix have been the two applications I use the most for a long time. In general, I make choices based on my mood, and I believe these preferences are reflected in my usage of these two platforms. I wanted to visually explore the connection between them.

# Dataset Description

I used Netflix viewing history and Spotify streaming history to analyze cross-platform entertainment behavior. The Netflix dataset includes timestamps, titles but lacks genre information. Similarly, the Spotify dataset provides track details, play durations, skips, and platform information without genre labels. To address this, I used the Spotify Open API and TMDb API to find the genres of the tracks and movies. Additionally, I created a custom movie list based on my Netflix data in TMDb, which can also be accessed here. By combining the enriched datasets, I am able to perform a comparative analysis of video and audio streaming habits with genre information included.

https://www.themoviedb.org/list/8506092-dsa210?view=grid

[NetflixViewingHistory.zip](https://github.com/user-attachments/files/17964855/NetflixViewingHistory.zip)


[Spotify Extended Streaming History.zip](https://github.com/user-attachments/files/17964856/Spotify.Extended.Streaming.History.zip)

# Project Idea

The goal is to identify patterns in entertainment consumption, examine the relationships between Netflix genres and Spotify preferences, and generate insights that can be used for personalized content recommendations. Key questions include: How do users allocate time between these platforms? Are there connections between the genres of watched shows and listened music? 

# Project Plan

The project started with data cleansing and harmonization of Spotify and Netflix data. Following that, we explored genre preferences, temporal allocation of entertainment, and the distribution of Turkish songs and movies over time, while also comparing the genres and analyzing the time spent on movies and songs.

Exploratory data analysis (EDA) was conducted using visualizations, including:

Top 10 Most Listened Genres, Artists, and Songs
Yearly Ratio of Turkish Movies Watched to Total Movies Watched
Overall Ratio of Turkish Movies Watched to Total Movies Watched
Total Number of Items Watched per Year on Netflix
Ratio of Turkish Songs to All Songs Listened to on Spotify
Listening Durations Over the Years
Correlations Between Genres of Movies and Songs
Correlation Between Listening to Turkish Songs and Watching Turkish Movies
Correlation Between Time Allocated to Listening to Music and Watching Movies



# Tools and Technologies

In this project, I utilized several key technologies to analyze and visualize the data. The primary programming language was Python, with libraries like pandas for data manipulation, NumPy for numerical operations, and scikit-learn for machine learning tasks. For data visualization, I used Matplotlib and seaborn to create various plots such as bar charts, scatter plots, and correlation heatmaps. To enrich the data, I integrated the Spotify Open API to fetch genre information for tracks and the TMDb API to gather movie genres from the Netflix data. Jupyter Notebook served as the development environment for data exploration, model building, and visualizations. These technologies combined allowed me to explore entertainment consumption patterns and develop insights across both platforms.




