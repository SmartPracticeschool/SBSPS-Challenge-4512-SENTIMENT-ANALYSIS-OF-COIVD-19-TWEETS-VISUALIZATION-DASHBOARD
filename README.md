# SBSPS-Challenge-4512-SENTIMENT-ANALYSIS-OF-COIVD-19-TWEETS-VISUALIZATION-DASHBOARD
This notebook consists of a simple and efficient code to perform sentiment analysis on coivd-19 tweets and segregate them as positive negative and neutral tweets. The analysis is performed using TextBlob library from python and regular expressions(re) library is used for preprocessingthe tweets. The Data set for tweets were obtained from the kaggle repository https://www.kaggle.com/smid80/coronavirus-covid19-tweets. 

ABOUT THE DATASET
  
  Context
    
  This dataset contains the Tweets of users who have applied the following hashtags: #coronavirus, #coronavirusoutbreak, #coronavirusPandemic, #covid19, #covid_19


  From about 17 March, the dataset also included the following additional hashtags: #epitwitter, #ihavecorona

  This is the first dataset in the series, as the Data tab only displays 20 files at a time and I have been uploading files with a single day's worth of data. To ensure that     all files are visible to users and no files are too large, it seems prudent to create a second dataset to split the files into manageable groups of approximately half a         month. The first file also contains a file that matches country with country_code and may be useful for users.

  The second dataset (for early April, plus the final few days of March) is located here: https://www.kaggle.com/smid80/coronavirus-covid19-tweets-early-april
  The third dataset (for Tweets in late April) is located here: https://www.kaggle.com/smid80/coronavirus-covid19-tweets-late-april

  Content
    
  The dataset contains variables associated with Twitter: the text of various tweets and the accounts that tweeted them, the hashtags used and the locations of the accounts.

  Note that due to the large volume of Tweets, there may be some gaps for some hashtags (not all Tweets with a given hashtag may be captured). Because some hashtags are used     less frequently than other hashtags, less frequently used hashtags may span a longer period of time (going back earlier) than more frequently used hashtags. The hashtag         "#coronavirus" seems to be the most frequently used - despite scraping 500,000 Tweets, there was no overlap between Tweets with this hashtag in version 1 and version 5,         therefore gaps remain.

  The retweets argument has been set to FALSE, so this dataset does not include retweets (although a count of retweets is provided as a variable).

  
