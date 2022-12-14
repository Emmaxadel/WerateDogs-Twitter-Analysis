# WeRateDogs Twitter Analysis
**WeRateDogs** is a Twitter account that rate people's dog and make humorouos comment on them. They are best known for their ratings which can range higher than an hundred percent. Cool, Right? Yeah.


In this analysis, tweets data were wrangled (gathered, assessed, cleaned), and visualized to draw meaningful insights from.

![Good_dog_brent_2](https://user-images.githubusercontent.com/82924138/188266660-37b2aadd-8c81-4b0e-ae5b-19662802057d.jpg)

The wrangling process is divided into three categories - `Data Gathering`, `Assessing Data`, and `Cleaning Data`.

## Data Gathering
The data used for analysis were sourced from 3 different sources:
1. A locally downloaded CSV file - `twitter-archive-enhanced.csv`. The CSV file contains information about the tweets such as the source of tweet, tweet id, tweet text, tweet URL, ratings and dog stage.

2. A programmatically downloaded TSV file - `image_predictions.tsv`. The TSV file was downloaded from udacity's server using the python's requests library. The TSV file contains the prediction of the breed of dogs rated in the tweets. The predictions were generated by running the dog's picture(s) found in the tweet in an image prediction machine learning algorithm.

3. A Scraped data from twitter. Python's Twitter API, tweepy was used in scraping more information about the tweets in the `twitter-archive-enhanced.csv` dataset. Using the tweet id in the dataset, retweet count and favorite count were scraped and stored in dataframe.

## Assessing Data
Practically, datasets in the real world are rarely clean or fit for analysis. There is always a need for cleaning and transforming the dataset(s). In this analysis, before cleaning, the datasets gathered were assessed both visually and programmtically, after which the issues encountered were documented under quality and tidiness category.

## Cleaning Data
The issues documented in the data assessment section of the project were cleaned thorouhgly in this section. The Cleaning was done in the `Define-Code-Test` framework. 

## Storing and analysis
After wrangling, the cleaned dataset was stored in `twitter_archive_master.csv`. More analysis and visualizations were done on the cleaned dataset annd great insights were drawn from it.
__________
The Wrangling efforts are documented in the `wrangle_report.html` while the insights drawn from the analysis are documented in the `act_report.pdf`
__________
Follow through in the notebook and I hope you'll love it.

Gracias! ????
