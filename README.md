# IPL dataset analysis and predection
Indian premiere League is a is a professional Twenty20 cricket league, contested by ten teams based out of ten Indian cities.

Dataset is used from kaggle: https://www.kaggle.com/ramjidoolla/ipl-data-set

The notebooks are on kaggle here: https://www.kaggle.com/ramjidoolla/ipl-data-set/code?datasetId=872854&sortBy=dateRun&tab=profile
# Goal 
The goal is to be able to predict the winner of next matches from past records and the teams playing.
# Steps
### Cleaning: In cleaning nulls are handled, and values are inspected to see best way to deal with every null value
* EDA: Get insights from data to get the best features in predection 

## Most important insights
* from 2008 to 2019 teams are not playing in every season; Some teams played just one season and some just missed two seasons.

![image](https://user-images.githubusercontent.com/59888340/140636837-d8a6620e-24ce-4b5c-8845-8ef9fff479bd.png)
* Some rivals have a lot of matches between each others and others meats rarely

![image](https://user-images.githubusercontent.com/59888340/140636924-e8f9cb55-4d57-4150-bd11-06b2ef066759.png)

* Every city has its own champion team which has the most winning percentage in it
![image](https://user-images.githubusercontent.com/59888340/140636945-4c965703-393e-4f69-b01b-f26dea176dda.png)

* Teams vary in thier winning rates against other teams which can be a good feature to determine how hard the match is

![image](https://user-images.githubusercontent.com/59888340/140637006-42d84aaf-39de-4191-ab20-11ca64e77f0c.png)

### Features engineering

Most important features are time dependent in this time series data. 

Most important features turned to be:
### Modeling 
The data is small, so automl was used to devolop a base model on normal featuers and a good model on the new features and compare results 
