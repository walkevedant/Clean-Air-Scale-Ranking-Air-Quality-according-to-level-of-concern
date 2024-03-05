# Clean Air Scale : Ranking Air Quality according to level of concern

This project aims at ranking the location based on its air quality with use of Machine Learning and Deep Learning techniques. The measures of air quality are different meteorological factors like temperature, humidity, etc.

The data has shape of 9,82,170 rows and 38 columns. The data is collected at various locations in Pune city from Jan 2021 to Jan 2022 by Pune Smart City Development Corporation Limited.

The level of concern of air quality is represented by column "Air Quality Rank" which has interger values ranging from 0 to 5 and its encoding is as follows,

Air Quality Rank--------->Level of Concern

5 --------> Good

4 --------> Moderate

3 --------> Unhealthy for sensitive group

2 --------> Unhealthy

1 --------> Very Unhealthy

0 --------> Hazardous

I have implemented K-Nearest Neighbors, Decision Tree, Naive Bayes and Neural Network using Sk-learn and Keras libraries. 

The Decision Tree Classifier algorithm worked best with accuracy score of 0.99 and 0.97 on train and test data respectively.

