# [Louis's Portfolio](https://github.com/grillon6u/Louis_Portfolio)

This repository presents all my personal projects and work related to data science. The repository is split in three sections: **Analytics**, **Data Science** and template&images. Feel free to **clic on any project** to go visualize more details on GitHub and find the full code and explanation, and notebooks that will explain more in-depth each step! All projects, except the PowerBi one, are done with Jupyter Notebooks. If you cannot open Jupyter Notebooks, don't worry, you will find an html version of each project that you can open with any browser.

## [Analytics projects](https://github.com/grillon6u/Louis_Portfolio/tree/main/Analytics-projects)

This section contains all projects and work related to Analytics. This means, all projects related to the following topics: Data Analysis, Mining and Visualizations. 
For now, it contains three distinct projects: multiplayer survey analysis, powerbi-training, and hackerrank SQL solutions. No further projects are planned for now.

### [Project 1: Multiplayer market analysis](https://github.com/grillon6u/Louis_Portfolio/tree/main/Analytics-projects/market_analysis_multiplayer_survey)

Topics: **Survey designing**, **Data cleaning**, **Data engineering**, **Data processing**, **Data visualization**, **Python dashboard**, **Hypothesis testing**, **Natural Language Processing**

This analysis was done as part of a much larger personal/secret project about the development of a mobile application. (The whole project is in french, don't worry it's the only one). Feel free to look in more details at the visuals in the notebook and how they are created.
The objective of this project was to gather data about the behaviour of multiplayer videogame players, and in particular who and how do they find people to play with. It involves several technical skills used during the different steps of the project:

1. Designing and forward a survey
2. Connecting to a dataset online
3. Cleaning and preparing the dataset (python, pandas, numpy)
4. Analysing each of the types of answer, and splitting them thanks to other answers (matplotlib, seaborn)
5. Create hypothesis about the data, and statistically confirm (or reject) them. (Stats, Chi square testing)
6. Use Natural Language Processing in order to analyze the questions that could have text answers. (nltk, textblob)
7. Sum-up our results from a business perspective.

**Result:** The project ended up successful, as it enabled me to correctly identify the potential customers and their characteristics for the mobile application project. In addition to that, it even provided new ideas for functionalities!


![Example of playing frequency visualization](template%26images/images/market.jpg)

### [Project 2: PowerBI training](https://github.com/grillon6u/Louis_Portfolio/tree/main/Analytics-projects/PowerBI-training)

Topics: **Data engineering**, **Data modelling**, **Data acquisition**, **Data cleaning**, **Data processing**, **ETL**, **Business Intelligence**, **Data visualization**, **Measure calculation**, **PowerBI dashboard**, **Artificial Intelligence**

This project was done during my time training in PowerBI. It consists in the building of dashboards relating to different datasets. Two distinct dashboards were made: AW dashboard, and AI dashboard.

#### [AW dashboard](https://github.com/grillon6u/Louis_Portfolio/tree/main/Analytics-projects/PowerBI-training/AdventureWorks_Report)

This dashboard is a classical one, and relates to several different tables found in the AW files folder. Those tables can be found as ressources on the internet, or accessed directly in the Microsoft PowerBI ressources.
The building of that dashboard involved three main steps:

1. Connecting to each of the sources, and formatting them
2. Data modelisation (linking the tables regarding their type and their primary and foreign keys)
3. Creating the metrics that we want to visualize using the DAX language
4. Visualising those KPIs in the best way possible (exploring different types of plot, and how their context interact)

![Main interface of the dashboard](template%26images/images/AW.jpg)

#### [AI dashboard](https://github.com/grillon6u/Louis_Portfolio/tree/main/Analytics-projects/PowerBI-training/Power_BI_AI_Visuals)

This dashboard only connects to one source (kickstarter projects and their results). The main objective was here to explore the AI features of powerBI, as seen in the report.

**Result:** The two powerBI dashboards resulted in clear and easy-to-use visuals, that are transforming raw data into powerful key indicators. In addition to that, it enabled me to improve my powerBI skills.

![Main interface of the dashboard](template%26images/images/AI.jpg)

### [Project 3: Stock market trading](https://github.com/grillon6u/Data_Science_projects/tree/main/Analytics-projects/Stock%20Trading)

Topics: **Stock trading**, **Sentiment analysis**, **wallstreetbets**, **Algorithmic trading**, **Data visualization**, **Trading bot**, **MACD**, **Natural Language Processing**

This project's goal is to analyze data from different subreddits (wallstreetbets, stockexchange,...) in order to choose in which stock to invest for a given day, and then to actually invest in it at the right time, in order to make a measurable profit. (This project also involved understanding how the stock market actually works). The main steps of the project are:

1. Measuring the evolution of the number of times each stock is mentionnent in those subreddits (python, praw)
2. Combining those results with the evolution of the sentiment (the positivity) of those quotes, in order to identify the stocks (AAPL, GME, ...) that have a good trend from a social media point of view (pandas, nltk)
3. Adding stocks that are trending on yahoo finance, while parsing it (mybeautifulsoup, request, html)
4. Getting live data about those stocks (yfinance)
5. Chosing when to buy and sell those chosen stocks using a statistical approach (MACD, signal line)
6. Automating the choosing, selling and buying by scheduling the tasks with a bot.


![Sentiment](template%26images/images/sentimentTickers.PNG)
![Sentiment](template%26images/images/AAPL.PNG)
![Sentiment](template%26images/images/MACD.PNG)

**Result:** The project was a success, and ended up in an operational, automated and successful trading bot! In addition to that, it enabled me to improve my knowledge of the trading world.

### Hackerrank SQL

Topics: **Data engineering**, **SQL**

This file is a simple text file, where I keep my answers to some Hackerrank SQL challenges.

### Shout out

I would like to thank:
- The Udemy PowerBI course, which was very useful during the building of the dashboards
- Hackerrank website, which gives incredible challenges in a lot of languages, and help you improve your skills (https://www.hackerrank.com/)
- My friends Najib and Matta, who work with me on the big personal project, especially the multiplayer analysis project.

## [Data science projects](https://github.com/grillon6u/Louis_Portfolio/tree/main/Data-science-projects)

This section contains all projects and work related to Data Science. This means, all projects related to the following topics: Webscrapping, Data exploration, Machine Learning, Deep Learning, Natural Language Processing.
For now, it contains three distinct projects: housing prediction, tennis sentiment analysis and computer vision and classification using ML and Deep Learning.
Further projects are still work in progress and will soon be added: computer vision (face mask detection) using deep learning.

### [Project 4: Housing prediction regression (EDA, ML)](https://github.com/grillon6u/Louis_Portfolio/tree/main/Data-science-projects/housing_prediction_regresssion)

Topics: **Data cleaning**, **Exploratory Data Analysis**, **Data Mining**, **Pipelines**, **Python**, **Feature Engineering**, **Machine Learning**, **Supervised regression**, **Parameter optimization**, **Ensemble Learning**

This project consists in the analysis and prediction of housing prices (regression problem). The dataset used is a very famous one in the data science community, and can also be found with the link in the python notebook directly.
The project consists in several steps:

1. Importing the data
2. Exploratory Data Analysis (using pandas, klib, pandas-profiling)
3. Feature Engineering (creation of the pipelines)
4. Training of Machine Learning models (sklearn, xgboost)
5. Fine-tuning those models (gridsearch, randomizedsearch)
6. Combining them into one even more performant model using ensemble learning.


![EDA of the housing prices in the Californian region](template%26images/images/house.jpg)

![Key insights about the target metrci using klib](template%26images/images/eda.jpg)

![Example of a decision tree applied to our dataset](template%26images/images/DT.jpg)

**Result:** The project was successful, and provides a powerful Machine Learning model, that can predict with high accuracy (40K) the price of a house, given specific features.

### [Project 5: Tennis sentiment analysis (Webscrapping, twitter scrapping, NLP)](https://github.com/grillon6u/Louis_Portfolio/tree/main/Data-science-projects/tennis_sentiment_analysis_using_NLP_and_webscrapping)

Topics: **Webscrapping**, **Data visualization**, **Python**, **Social Network scrapping**, **Natural Language Processing**, **Sentiment Analysis**

This project's goal is to compare the global popularity of the most famous tennis (one of my passions) players on twitter. The project consists in several steps:
1. Webscrapping wikpedia in order to get the best players of the moment (using python, pandas, myBeautifoulSoup, html)
2. Creating their twitter names using basic string methods
3. Connecting to twitter and retrieving tweets about the players (using tweepy)
4. Analsying the content of those tweets, and calculating their polarity (how positive they are) using Natural Language Processing (nltk, textblob)
5. Plotting their popularity as a rolling moving average

![Rolling moving average of Novak Djokovic's popularity on twitter](template%26images/images/novak.PNG)

**Result:** The project was successful, and can be used to accurately measure the popularity of a given tennis player on twitter for the previous week. You can find a nice presentation of the project and its complete result on GitHub.

### [Project 6: Computer Vision and Image classification using Machine Learning and Generative Adversial Networks](https://github.com/grillon6u/Data_Science_projects/tree/main/Data-science-projects/Image%20classification%2C%20Dimensonality%20reduction%20and%20Generative%20Artificial%20Networks)

Topics:  **Computer Vision**, **Data cleaning**, **Dimensonality reduction**, **Clustering**, **Machine Learning**, **Ensemble Learning**, **Deep Learning**, **Generative Adversial Network**, **Stacking**

This project's goal is to classify images of hand written pictures, using Machine Learning and Deep Learning techniques. Then, in a second time, we will try to re-generate more pictures using Generative Adversial Networks. The main steps of the project are:
1. Importing the data, and visualizing the pictures of the dataset, in order to understand what we are dealing with
2. Preprocessing the data, using unsupervised learning (PCA, clustering)
3. Cleaning the images to improve performance
4. Trying out Machine Learning and Deep Learning models (Logistic regression, SVM, KNN, RandomForest, XGBoost, MultiLayer Perceptron)
5. Measuring their accuracy, and trying to improve it by fine-tuning their hyperparameters
6. Apply Ensemble Learning (Bagging, Stacking) to the models that are performing the best
7. Data augmentation (improving our dataset), by creating new images from the ones we already have, from simple rotations and translations, to GANs.

![PCA](template%26images/images/scrrenPCA.PNG)
![training](template%26images/images/deepl.PNG)
![Final confusion matrix](template%26images/images/confusionMatrix.PNG)
![Gif of GAN generating](Data-science-projects/Image%20classification%2C%20Dimensonality%20reduction%20and%20Generative%20Artificial%20Networks/Images/dcgan.gif)

**Result:** The project was successful, and ended up in a complex Machine Learning model, able to accurately (97%) classifiy hand written picture. It is fast (using a PCD), and can compete with a tested deep learning model. In addition to that, a Generative Adversial Network is also trained to create hand written pictures on itself.

### Shout out
I would like to thank:
- Aurelien Geron, who wrote "Hands-on ML", which I highly recommend
- Nicholas Renotte and Ken Jee, whose articles and tutorials helped me a lot.
- TensorFlow tutorials about deep learning, neural networks.
- Jason Brownlee, for his tutorials and articles about computer vision with keras

## template&images

This section contains a data science project template, with the important steps and imports already included, and the images used in this github. Feel free to use it!
