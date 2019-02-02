# Car Brand Analysis

****************************************************************************
I have been leaning on how to do Text Analytics and Natural Language Processing on wide platform of social media like Public Forums (Edmunds, Yelp etc.), Instagram, Twitter etc.

This is the first Project of the Series #User-Generated-Content-Analysis. Since this is a learning process, you will see a gradual improvement in the techniques used and also reduction in the number of assumption. 

As for this project: 

Things Learned:
* Lift Calculation
* Word-Frequency count
* Natural Language Processing
* Stemming & Lemitization
* Importance of word replacement

Assumptions:
* Sentiment is positive
****************************************************************************

# Project 1 of Series #User-Generated-Content-Analysis

The aim of this project is to gain useful insights of different car brands based on the analysis of social media conversations on Edmunds

The flow of the project goes as follows:

* Create a crawler to fetch 4k-5k recent posts from a General toppics forum. The idea behind using a general forum and not a specific forum is to have multiple brands and models being discussed without one of them being the focal point. 

* After pre-processing of collected data the top 10 brands being discussed are selected for further analysis. This is done by replacement of individual car names with the brands followed by frequency count of brand names.

* Calculating Lift scores to find association between the brands and plotting the MDS or other equivalent plots for the same.

* Finding the 5 most frequently discussed attributed of the cars in the discussions. This is done by calculating the frequency count of words in the posts and then replacing the relevant words with features. Now pick 5 top five brands. The aim is to find which features are associated with which brand.

The intention behind doing all these steps is to:

To act as an analytics consultant gather useful insights for key people like (i) product manager, and (ii) marketing/advertising manager of these brands. Also the secondary aim is to find out which is the most aspirational brand in your data in terms of people actually wanting to buy or own and what are the business implications for this brand?
 
