# HACK_THE_FEED_DICEY_TECH_SOLUTION
The project uses the power of data analytics, statistical analysis, and text analytics to answer business questions from the data.

## Project Structure:

#### Notebooks

1. Hack_Feed_Solution_1.ipynb
   
2. Hack_Feed_Solution_2.ipynb

#### Project Objectives, Business Insight, and Recommendations

  1. Project_Solution_Report.pdf
     
  2. DiceyTech-Solution-submit.pdf

## Project Objectives

Given the post data on each social media platform, the overall objectives are:

•	**Improved Brand Identity** – This involves the implementation of a machine learning model for post sentiment classification to detect the post's tone before posting on social media platforms.

•	**Content Categorization and Summarization** – This involves implementing a topic modeling approach in categorizing posts for quality engagements.

•	**Content Strategy** – This involves the implementation of a regression analysis model for determining the effect of content structure on engagements across each social media platform.

•	**Automation** - This involves the implementation of a machine learning model, topic modeling, and sentiment analysis model to increase competitive advantage and efficiency. 

## Business Insight (Key Findings)

•	Maximum number of posts were recorded in 2022, across all platforms.

•	Facebook performs better in terms of engagement quality and quantity, than all other platforms.

•	There is a strong correlation between impressions and engagements of posts on Twitter and LinkedIn with 68% and 62% respectively, while there is less correlation on Twitter and Facebook with 24% and 5% respectively.

•	The most engaging content type on Facebook is Text, Instagram is Video, and Twitter and LinkedIn are photos.

•	The peak post engagement day of the week on Facebook is Thursday, Instagram is Friday, Twitter is Monday, and LinkedIn on Thursday.

•	The peak post engagement time on Facebook is 5:00 PM, Instagram is 10:00 AM, Twitter is 5:00 PM, and LinkedIn is 12 PM.

•	The posts by Aramide Salami on (Facebook & Instagram) and Damilare Oyekanmi (on Twitter & LinkedIn) have many quality engagements across the platforms. Unknown is a missing sent by name that has a quality engagement on Facebook, Instagram, and LinkedIn.

•	A shorter length of a post drives more engagement on Facebook and Instagram, while a longer length (medium) drives more engagement on Twitter and LinkedIn.

•	Hashtags have great influence on Instagram and LinkedIn, while it has less influence on Facebook and Twitter.

•	The Net sentiment scores across Facebook, Instagram, Twitter, and LinkedIn are 62.95%, 66.10%, 62.08%, and 68.48% respectively.

•	Damilare Oyekanmi’s content is excellent on Instagram, Twitter, and LinkedIn, while Kemi Amoo is good on Facebook posts.

•	Neutral Content tone drives more engagement on average on Facebook, Instagram, and LinkedIn, while Negative content tone drives more engagement on Twitter.

•	Most posts are focused on Investment, Insurance, policy, and call-to-action advertisements.

•	 Call to action advertisement’s post has a more engaging pattern than all other topics.

* Celebration's season post drives more engagement in quality, after call-to-action advertistment.

•	Most frequently used words are tailored using Stanbic ibtc.

•	A machine learning model (Less Carbon Emission) that can be deployed with 85% accuracy should be used to classify the tone of a post before posting on the platforms.

## Recommendations

•	Incentivized banking during celebrations season to bring more customers.

•	Implementing Artificial Intelligence solutions to improve brand image, efficient content review, proactive crisis management, and cost efficiency is needed to have a highly competitive advantage to acquire more customers.

•	Neutral Content tone should be more employed to drive engagement on Facebook, Instagram, and LinkedIn, while Negative content should be used on Twitter.

•	Creating different tone messages on each platform to drive more engagement from customers.

•	Recognizing and rewarding outstanding content creators (sent by) to boost motivation, setting standards to reduce the employee attrition rate in the organization.

•	Driving cross-platform traffic by using the most engaging content type (detailed text for Facebook, quality video snippets for Instagram, and quality Photo for Twitter and LinkedIn) to drive optimal engagement from customers.

•	Optimized post scheduling by posting during peak engagement times to increase interactions and potential wider reach.

•	Tailored content to enhance content visibility and efficient content creation.

## Solution Workflow Graphics

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/Slide1.png?raw=true)

### Note

**The solution's workflow can be seen on Hack_Feed_Solution_1 and Hack_Feed_Solution_2 (.ipynb)**

## METHOLOOGY

### Problem Statement

The problem statement is to analyze the bank’s social media platforms traffic, generated from the accumulated posts, and optimize its use to generate quality insights and proffer solutions to the observed challenges.

### Data Understanding

This is the method used in understanding the dataset, by checking the total rows and columns, identifying missing values, and checking if there are duplicate values from each data and data type.

### Data Cleaning

This is when the dataset is being cleaned to derive meaningful insight to aid the business goals.
•	Drop any column(s) with more than 70% missing values.

•	Drop any row(s) with missing posts.

•	Drop features with missing engagements.

•	Drop redundant features.

•	Drop some columns redundancy using correlation (i.e., they have the same trend)

•	Missing values imputations (when needed)

•	Text data cleaning

### Feature Engineering

•	Extract year, month, week, and hours from date time features to capture seasonal trends.

### Data Insight Workflow

•	Perform univariate and bi-variate analysis to understand patterns in our dataset (Data Visualization). 

•	Time Series plot to understand trends over time.

•	Correlation analysis to find relationships between variables in the dataset.

•	Regression Analysis to predict patterns of content creation in relation to engagements.

•	Sentiment Analysis to understand the tone of the post to maintain consistency of the brand image.

•	Topic modeling to understand the content strategy optimization.

•	Word cloud analysis to understand the pattern of the text.

•	Machine Learning models to increase post efficiency.

•	Interpretable machine learning to improve the trustworthiness and transparency of the machine learning models.

### Data Visualization

**Note: Explore Full workflow in the Jupyter Notebook**

#### Post Engagements Quality and Quantity

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/Network_analysis1.png?raw=true)

**Observation**

. Facebook performs better in terms of engagement quality and Quantity

. Twitter has more Engagement Quality than Instagram, while Instagram has more Engagement Quantity Twitter.

. LinkedIn is the least for both.


### Correlation Analysis between Engagements and Impression

#### Facebook

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/FbEI.png?raw=true)

**Observation**

* We observed a linear trend between Engagements and Impressions

* They are partially positively correlated with close to 24%

* They are statistically significant (p-value is less than 0.05)

#### Instagram 

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/Ins.png?raw=true)

**Observation**

* We observed a linear trend between Engagements and Impressions

* They are partially positively correlated, with close to 5%

* They are statistically significant (p-value is less than 0.05)

#### Twitter

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/Twit.png?raw=true)

**Observation**

* We observed a linear trend between Engagements and Impressions

* They are partially positively correlated, with close to 62%

* They are statistically significant (p-value is less than 0.05)

#### Linkedln

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/Linkedln.png?raw=true)

**Observation**

* We observed a linear trend between Engagements and Impressions

* They are partially positively correlated, with close to 68%

* They are statistically significant (p-value is less than 0.05)

#### Top 20 words

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/word_c.png?raw=true)

#### Sentiment Analysis Word Cloud

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/word.png?raw=true)

#### Machine Learning Models Accuracy

![alt text](https://github.com/nasirudeenraheem/HACK_THE_FEED_DIEY_TECH_SOLUTION/blob/main/Analysis_Images/ml.png?raw=true)

**Observation**

* Extra Tree Classifier is the most accurate model, and it will be able to classify our post sentiment correctly with 85% assurance.

