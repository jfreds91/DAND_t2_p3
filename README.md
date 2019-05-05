# Analyzing WeLoveDogs tweets
## DAND_t2_p3
Jesse Fredrickson

## Motivation
The purpose of this project is to scrape, clean and analyze tweets from the WeRateDogs twitter account.

## Files
**wrangle_act.ipynb:** this is the main iPython notebook where I perform all of my webscraping, data cleaning, preprocessing, and analysis.

**wrangle_report.ipynb:** in this notebook I explicitly explain all of the gathering, assessing, and cleaning operations performed in the main notebook

**act_report.ipynb:** in this notebook, I discuss my final findings and provide visualizations from the main notebook

**tweet_archive.csv:** A dataframe consisting of tweets from the WeRateDogs twitter account

**image_predictions.csv:** A dataframe containing each tweet's id along with a neural net analysis of the associated image, attempting to guess the breed of dog in the image. It is retrieved programmatically from a url offered by Udacity

## Results / Instructions
Download the **wrangle_act.ipynb** file and ensure that you have the requisite python modules, including pandas, numpy, tweepy, requests, os, time, json, datetime, fuzzywuzzy, matplotlib, re, seaborn, and statsmodels. All results are documented in **act_report.html**