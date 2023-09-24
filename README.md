# Twitter-user-gender-classification
# Introduction
With the rise of social media in recent years, there has been a surge in interest in automatically identifying users based on their informal content. In this context, the research of other aspects intrinsic to users, such as political inclinations, personality, and gender, as well as the categorization of users in demographic categories such as age, ethnicity, origin, and race has gained a lot of interest notably based on Twitter data. The current work focuses on the job of gender categorization in tweets written in English by extracting gender expression linguistic cues utilizing 25 attributes, which are often employed on text attribution tasks.
# Data Source
The Data has been extracted from Kaggle. The dataset consists of 20050 rows and 26 columns. Among 26 columns there are 25 predictor variables and 1 target variable which is gender in this case. 
The link to the data source is given below. 
Link https://www.kaggle.com/crowdflower/twitter-user-gender-classification/
# Methodology
Step 1- Install Classifiers and import all the important libraries.

Step 2- Read Data from CSV file. 

Step 3- Show the shape of Data, and check the Information of it. 

Step 4- Dropped redundant columns from the DataSet. 

Step 5- We check for null values in the DataSet, if there are any, we drop them.

Step 6- Count the variables of the ‘gender’ column. 
 
Step 7- Encode the ‘male’ as 1 and ‘female’ as 0. 

Step 8- text cleaning.

Step 9- Tokenization and Lemmatization of Cleaned column and remove stop words(English) using NLTK library. 

Step 10- Add new column to DataSet of “DescriptionList”. 

Step 11- Bag of Words (we will take top 5000 feature).

Step 12- (make an array from Counter vector of the "DescriptionList"). 

Step 13- Split the Data into train and test Data.

Step 14- Show Plots of data.

Step 15- Applied classifiers (Decision tree, Random Forest, LogisticRegression) to get the ACCURACY.

Step 16- Show the Highest ACCURACY.

Step 17- View the classification report for test data and predictions. 

Step 18- Show The Result.








