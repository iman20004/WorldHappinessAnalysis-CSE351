# WorldHappinessAnalysis
### CSE 351 - Introduction to Data Science Final Project


## Project: What makes people in a country happy?
The World Happiness Report is a landmark survey of the state of global happiness that ranks countries by how happy their citizens perceive themselves to be. The report gains global recognition as governments, organizations and civil society increasingly use happiness indicators to inform their policy-making decisions. This project allows us to gain insight into the state of happiness in the world today.

#### Datasets:
The “world_happiness.zip” file on Blackboard contains happiness data for different countries from year 2015 to year 2019. We will treat data of year 2015 to year 2018 as the training set, and year 2019 data as the test set. Description of the data fields can be found on the FAQ page of World Happiness Report: https://worldhappiness.report/faq/
EDA (10 points):
Get familiar with the dataset and decide what features and observations will be useful. Make good use of visualizations. Specific tasks may include but are not limited to:
- Merge and clean the data. Explain what you did.
- What are the central tendencies of happiness score over the years? Did they increase or
decrease?
- Which countries have stable rankings over the years? Which countries improved their
rankings?
- Visualize the relationship between happiness score and other features such as GDP,
social support, freedom, etc.
- Find out what features contribute to happiness. If you are the president of a country,
what would you do to make citizens happier?

#### Modeling and Question Answering (10 points):
The happiness rankings in the datasets are determined by happiness scores only. Now we want to predict the ranking using a machine learning approach. Build three models based on data from year 2015 to year 2018. Explain how each model works (briefly introduce the machine learning algorithms behind them). Predict the happiness ranking for the year 2019 (drop the “overall rank” and “score” columns first). Compare your rankings to the original rankings in “2019.csv”. How does each model perform? Invent your own formula to calculate happiness score using features of your choice.
