
# Chemistry YouTube Channels + Vidoes

## Description
This project uses YouTube APIs to gather data from YouTube on the most popular Chemistry-Based Channels.  We analyze metrics like their view counts, subscriber counts, and video counts.  We explore what it takes to be a successful Chemistry Channel on YouTube.

With more time, I might like to perform statistical tests to confirm the correlations seen and conclusions made.  
I might also like to analyze view counts for The Organic Chemistry Tutor's videos **back in 2019** - _before_ the COVID-19 pandemic.  

### Techniques highlighted:
- Data Wrangling via API Technology
- Data Cleaning
- Data Analysis & Visualization with Python
- Drawing Insights & Conclusions

### Conclusions:
- View count and Subscriber count show a strong positive correlation. Both are good indicators of channel popularity.
- Video count is weakly correlated with number of views.  That is, the channels with the most videos are not necessarily the most popular channels, and vice versa.  
- The most popular Chemistry videos on YouTube are those that cover fundational topics in chemistry.
The COVID-19 pandemic may have incentivized the most popular YT channels to keep publishing content after 2020.  That is, skyrocketing views upon school closures and the switch to online learning may have rewarded the "good" Chemistry Tutorial channels, thereby incentivizing them to keep creating content after 2020.

Note that these conclusions pertain to **Chemistry-based** YouTube channels.



## Instructions for Running the Script
This project requires a YouTube API to wrangle the data.

### Generate your own API key: 
1. Login to https://console.cloud.google.com/ with your google account.  
2. "Create Project" once logged in.  
3. Click "Enable APIs and Services".
4. Search for YouTube Data API v3. Click "enable" to **enable the API**.
5. Now API key can be created. Go to "Credentials" and click "Create Credentials", choosing "API key".
6. Copy the API key to be used in the next phase.

### Create an environment variable:
1. After cloning this project, run the following command in your terminal/local environment:
- export GOOGLE_API_KEY = 'api_key_copied_from_step6'
2. Ensure your API key was properly stored in the environment variable by running:
- echo $GOOGLE_API_KEY - you should see your API key returned.

The python script will now run as expected.  The script does not use so many API credits that you exceed the API quota for the day.


## Software Dependencies
Python version 3.9 is required when using YouTube APIs.

## Skills
Data Wrangling (via API technology), data cleaning, data analysis, data visualization, python code 

## Technology
Python modules: Pandas, Matplotlib, Seaborn

## Results
Exploring key metrics for the most popular Chemistry-based channels on YouTube, to provide myself with wisdom, insight, and recommendations in the event I make my own Chemistry-based channel. 


