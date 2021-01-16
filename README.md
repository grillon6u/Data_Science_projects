# Louis's Portfolio

This repository presents all my personal projects and work related to data science. The repository is split in three sections: Analytics, Data Science and template.

## Analytics projects

This section contains all projects and work related to Analytics. This means, all projects related to the following topics: Data Analysis, Mining and Visualizations. 
For now, it contains three distinct projects: multiplayer survey analysis, powerbi-training, and hackerrank SQL solutions. No further projects are planned for now.

### Multiplayer market analysis

This analysis was done as part of a much larger personal/secret project about the development of a mobile application. (The whole project is in french, don't worry it's the only one). Feel free to look in more details at the visuals in the notebook and how they are created.
The objective of this project was to gather data about the behaviour of multiplayer videogame players, and in particular who and how do they find people to play with. It involves several technical skills used during the different steps of the project:

1. Designing and forward a survey
2. Connecting to a dataset online
3. Cleaning and preparing the dataset (python, pandas, numpy)
4. Analysing each of the types of answer, and splitting them thanks to other answers (matplotlib, seaborn)
5. Create hypothesis about the data, and statistically confirm (or reject) them. (Stats, Chi square testing)
6. Use Natural Language Processing in order to analyze the questions that could have text answers. (nltk, textblob)
6. Sum-up our results from a business perspective.


![Example of playing frequency visualization](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/marketAnalysis.PNG)

### PowerBI training

This project was done during my time training in PowerBI. It consists in the building of dashboards relating to different datasets. Two distinct dashboards were made: AW dashboard, and AI dashboard.

#### AW dashboard

This dashboard is a classical one, and relates to several different tables found in the AW files folder. Those tables can be found as ressources on the internet, or accessed directly in the Microsoft PowerBI ressources.
The building of that dashboard involved three main steps:

1. Connecting to each of the sources, and formatting them
2. Data modelisation (linking the tables regarding their type and their primary and foreign keys)
3. Creating the metrics that we want to visualize using the DAX language
4. Visualising those KPIs in the best way possible (exploring different types of plot, and how their context interact)

![Main interface of the dashboard](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/pBI_AW.PNG)
#### AI dashboard

This dashboard only connects to one source (kickstarter projects and their results). The main objective was here to explore the AI features of powerBI, as seen in the report.

![Main interface of the dashboard](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/pBI_AI.PNG)

### Hackerrank SQL

This file is a simple text file, where I keep my answers to some Hackerrank SQL challenges.

### Shout out

I would like to thank:
- The Udemy PowerBI course, which was very useful during the building of the dashboards
- Hackerrank website, which gives incredible challenges in a lot of languages, and help you improve your skills (https://www.hackerrank.com/)
- My friends Najib and Matta, who work with me on the big personal project, especially the multiplayer analysis project.

## Data science projects

This section contains all projects and work related to Data Science. This means, all projects related to the following topics: Webscrapping, Data exploration, Machine Learning, Deep Learning, Natural Language Processing.
For now, it contains two distinct projects: housing prediction, tennis sentiment analysis.
Further projects are still work in progress and will soon be added: computer vision (face mask detection) using deep learning, image classifier using machine learning / image generator using GANs.

### Housing prediction regression (EDA, ML)

This project consists in the analysis and prediction of housing prices (regression problem). The dataset used is a very famous one in the data science community, and can also be found with the link in the python notebook directly.
The project consists in several steps:

1. Importing the data
2. Exploratory Data Analysis (using pandas, klib, pandas-profiling)


3. Feature Engineering (creation of the pipelines)
4. Training of Machine Learning models (sklearn, xgboost)

5. Fine-tuning those models (gridsearch, randomizedsearch)
6. Combining them into one even more performant model using ensemble learning.

![EDA of the housing prices in the Californian region](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/screenHouse.PNG)

![Key insights about the target metrci using klib](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/housingEDA.PNG)

![Example of a decision tree applied to our dataset](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/DecisionTree.PNG)

### Tennis sentiment analysis (Webscrapping, twitter scrapping, NLP)

This project's goal is to compare the global popularity of the most famous tennis (one of my passions) players on twitter. The project consists in several steps:
1. Webscrapping wikpedia in order to get the best players of the moment (using python, pandas, myBeautifoulSoup, html)
2. Creating their twitter names using basic string methods
3. Connecting to twitter and retrieving tweets about the players (using tweepy)
4. Analsying the content of those tweets, and calculating their polarity (how positive they are) using Natural Language Processing (nltk, textblob)
5. Plotting their popularity as a rollong moving average
![Rolling moving average of Novak Djokovic's popularity on twitter](https://github.com/grillon6u/Data-Science-projects/blob/main/template%26images/images/Djokovic.PNG)

### Shout out
I would like to thank:
- Aurelien Geron, who wrote "Hands-on ML", which I highly recommend
- Nicholas Renotte and Ken Jee, whose articles and tutorials helped me a lot.

## template

This section contains a data science project template, with the important steps and imports already included. Feel free to use it!
