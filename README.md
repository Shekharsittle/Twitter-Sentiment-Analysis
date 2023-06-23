# Twitter-Sentiment-Analysis
## Problem Statement : 
 Perform sentiment analysis on a subset of a larger Twitter dataset. Identify trends, major
 topics of discussion, and their associated sentiments.
## Dataset
https://www.kaggle.com/datasets/kazanova/sentiment140
## Exploratory Data Analysis
* There were 1600000 rows and 6 columns, no null values present in datasets.
 ![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/4c3df030-e657-4d9e-86fa-2ba5e371f9fc)
* From the above graph , we can infer that distribution of negative and positive words are approximately same.
## Data Preprocessing
![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/4948b390-4eea-433f-99d1-11b45d9fe577)
Defined a function toremove any url ,punctuation , @ marks from the twittts and lemmetized the text for further model development.
## Model Development and Evaluation
Developed a Naive Bayes , Logistic classification, Support Vector Machine and Random Forest classifier models , among which logistic classifier performed best with accuracy of 80%.
![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/b3241502-6722-4fcc-a623-1bab7ea96538)
## RNN
Also developed a RNN model for classifying any tweet as negative and positive , upon which we can make an app by which we can judge whether the tweet is negative ir positive.The accuracy of the model came out to 77.28 percent which was quite good.
![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/7d18ba19-e61e-4b3f-beb2-96887604f073)
## Trending words
Also we have got some positive and negative trneding words from datasets. By help of these word we could know what are possible trends which are going on in the world .
![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/cbc1aa67-c8b2-4ddd-96c0-80c166421426)
![image](https://github.com/Shekharsittle/Twitter-Sentiment-Analysis/assets/127113185/bbd8b1ad-2c1b-451c-b563-b51bac4747b4)


