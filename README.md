# Business Understanding

## Overview

For this analysis we are  going to provide insight into public perception of Google versus Apple products through sentiment.  
We will be using multiple Machine Learning models for analysis

# Data Understanding
- Importing Key Python libries for data analysis and visualization
 - Loading Tweeter Sentiment  dataset using tweet.csv file
## Data Preparation

-Cleaning and preprocessing data prior to analysis

# Exploratory Data Analysis
#### Brand Analysis
![brand_category_distribution](https://github.com/user-attachments/assets/079f7160-f26e-412a-bbd7-044528e12a46)
#### Sentiment Analysis
![overall_sentiment_distribution](https://github.com/user-attachments/assets/5e6aa554-c3f4-4342-b04f-66dad6b9b022)
#### Tweet Counts
![sentiment_top_eight](https://github.com/user-attachments/assets/d799f1df-9848-44e3-ae5f-7a01a22a40e3)
#### Brand Analysis
![sentiment_by_brand_percent](https://github.com/user-attachments/assets/0b8c9f10-7b42-4cdf-9fe6-a1824ab2b59a)
![Sentiment_brand category_percent](https://github.com/user-attachments/assets/7155b712-7dcc-4d2a-a570-7284e16817e5)
#### ML Prediction
![Confusion_matrix_best_model](https://github.com/user-attachments/assets/9e46eac4-0d5e-497e-867a-1d4be06d8a28)
#### ML Comparison
![final_model_comparison](https://github.com/user-attachments/assets/6458c8d7-8fc0-4df4-bdd6-962e98da46cd)

# Conclusion

The data shows that Apple dominated the dataset (63.3%) of tweets compared to Google (18.89%) but both brands performed nearly identical in terms of sentimental distribution, which is quite interesting. The analysis revealed similar sentiment patterns between Apple and Google with both brands achieving approximately 83% positive sentiment,16-17% negative sentiment and minimal neutral responses. This is indicating that both tech heavyweights maintain strong positive public perception, even though there's rivalry. By achieving 87% accuracy in classifying tweet sentiment toward technology brands, we created a scalable solution that transforms manual social media monitoring into an automated process

## Limitations

Sentiment analysis system does face a few limitations that could be considered for future reference. The model relies exclusively on english language Twitter data that probably doesn't represent the broader, social media sentiment or global consumer opinions. Some technical limitations could include possible difficulty, detecting sarcasm and irony. There could be a model drift as language evolves. Data set size constraints can create potential blind spots for certain sentimental classes, and the traditional machine learning approach may not capture complex linguistic patterns.

## Recommendations

Some possible recommendations would be to possibly expand data collection on Twitter to possibly include Instagram, Facebook, Reddit and other review platforms to create a more comprehensive sentiment picture. You can also implement multilingual capabilities starting with Spanish, etc..

## Next Steps

Set up regular model maintenance with monthly performance checks and possibly quarterly retraining of the models.
