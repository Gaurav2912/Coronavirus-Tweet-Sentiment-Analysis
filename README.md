
# Cronavirus-Tweet-Sentiment-Analysis (ML classification NLP Project)

**Capstone project of Natural language Processing** 

**This project addresses the problem of sentiment analysis and to build a classification model to predict the sentiment of COVID-19.** 


That is, classifying tweets according to the sentiment expressed in them: extremely positive, positive, extremely negative, negative  or neutral.

![1_97iJ_XwezR6XD_1WY6VNng](https://user-images.githubusercontent.com/73479133/202843742-af51edcb-b460-48b2-b1e7-3d13894804b9.png)


<a href="https://www.freeiconspng.com/img/6071" title="Image from freeiconspng.com"><img src="https://www.freeiconspng.com/uploads/summary-png-icon-1.png" width="70" alt="Free Files Summary" /></a>

# ***Summary*** 
---

>The following topics were covered in this notebook:
- Downloading a real-world dataset
- Looking for null and missing values
- Try to get some insights from data
- Data Cleaning, Preprocessing and Feature engineering, converting text formet to bag of words . 
- Preparing a dataset for training
- Training and interpretation with different models
- Overfitting, hyperparameter tuning & regularization
- Predict and calculate sum evaluation metrics for model
- Making predictions on single inputs and its probability on LIME
- Model Persistence saving and loading the model


<p><img alt="Insight logo" src="https://drive.google.com/uc?export=view&id=14dpaeXX-ajsM8quwe3dCCdQdrdvf29iI" align="left" hspace="20px" vspace="20px" width="45" height="60" ></p>




# **Overall Conclusion**
---
---
---
<br/>

> **Examining Null Values**
* Location Column have approx 20 percent missing values.
* No missing values were found in the OriginalTweets and Sentiment columns.

<br/>

> **Exploratory Data Analysis**
- Length of the tweets is negatively skewed.
- Length of neutral sentiment tweet is positively skewed.
- As the location suggests, most of the places are from English speaking countries or country where people understand English, such as UK, USA, India, Canada, Australia etc., and among these most of them are also from the US and UK.
- The first quarter has the highest percentage of overall negative sentiment tweets as compared to the other.
-  By analyzing hashtags
  -  Most of the them are about corona virus outbreak and pandemic, Social distancing, lockdown , staying at home etc..
  - Due to the lockdown, people are also facing problems due to the closure of supermarkets, shortage of food, and running out of toilet papers.

<br/>

> **Natural Language Processing and Machine Learning**
- Even after passing through different machine learning models, we noticed that there is not much improvement in accuracy, so I changed the Sentiment feature to Binary class and the accuracy improved from 61 to 86 percent. 
- Among all models SGD gave best performance so I tune its hyperparameters using grid search with five fold stratified cross validation, and accuracy has increased to 87.5 percent.
- Area under ROC curve is 0.92 , area under precision-recall curve is 0.89.
