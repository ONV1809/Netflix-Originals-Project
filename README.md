# Netflix-Originals-Project
---
The purpose of this set of projects was to exemplify my Data Science skills within  various realms. The projects were centered around Netflix Originals (films), which are productions where Netflix either produced a given media themselves, or bought the exclusive streaming rights to that media. All files related to this project can be found in this repository.

## Overview + Structure
---
This project is contained within 4 Jupyter Notebooks, with each one exemplifying a different subset of skills. The notebooks are titled as follows:

- Netflix Originals - Dataset Creation.ipynb
- Netflix Originals - EDA.ipynb
- Netflix Originals - Recommendation Engine.ipynb
- Netflix Originals - ML

NOTE: Each Notebook contains a conclusion with a summary, limitations and future work.

The focus of the Dataset Creation Notebook was to create a Pandas dataframe for Netflix Original films from scratch. The list of films can be found at : https://en.wikipedia.org/wiki/Lists_of_Netflix_original_films. Using Beautiful Soup, film titles and other relevant data was scraped from each films unique infobox. Although this was a comprehensive Web Scrape with a lot of data collected, there were many missing values due to the inconsistent structuring of info-boxes. In order to solve this problem, I communicated with the OMDb API, which is a RESTful web service which can be used to return information about films that are listed on IMDb. Once missing values were dealt with, the remainder of the notebook was focused on Data Cleaning.

The purpose of the 2nd notebook was to perform an exploratory data analysis on the dataset that was created in the first notebook. Natural Language Processing transformations were undertaken on some variables in the Netflix Originals DataFrame and n-grams were used to find out the most common words/phrases in plot descriptions. The analysis is intended extract meaningful insights that can be used in real life situations to guide decision making processes in the entertainment industry. This notebook also allowed me to gain a better understanding of my data, which would later allow me to develop a more effective predictive model (of IMDb Scores).

The purpose of the 3rd notebook was to develop a recommendation engine for films in the Netflix Originals dataframe that was created in the first notebook. The end result was an interactive widget where a user can input a film title, with the widget returning the top 5 most similar films. The widget is lenient with user error and can adapt to movie titles that are incorrectly entered.

The final notebook was focused on developing an effective model for predicting IMDb scores for an unseen film. Pre-processing for ML took place in this notebook through feature engineering, as well as MLB processing and column transformations and scaling. In the second stage of this notebook, models were developed both with and without PCA to determine if a reduction in dimensionality boosted model performance. Model performance was assessed using Root Mean Square Error (RMSE) and R-Squared ($R^2$). Feature importance was also assessed.

## Skills Demonstrated in each Notebook
---
### Netflix Originals - Dataset Creation.ipynb
- Web Scraping with Beautiful Soup
- API interaction with OMDb API
- Data collection from multiple sources
- Handling missing data
- Data Cleaning and Transformation
- Pandas DataFrame Manipulation.
- Using Regular Expressions

### Netflix Originals - EDA.ipynb
- Exploratory Data Analysis (EDA)
- Data Visualisation using libraries like Matplotlib or Seaborn
- Statistical Analysis (t-tests to compare groups)
- Text Analysis and Natural Language Processing (NLP)
- n-gram Analysis
- Feature Engineering
- String Manipulation

### Netflix Originals - Recommendation Engine.ipynb
- Building a Recommendation Engine
- User-Interface Development for Interactive Widget
- Similarity Algorithms (Cosine Similarity and linear kernels)
- Handling user input and errors (fuzzy wuzzy)
- Data Filtering and Querying
- Using Regular Expressions
- String Similarity Techniques

### Netflix Originals - ML.ipynb
- Pre-processing for Machine Learning
- Feature Engineering
- Dimensionality Reduction using PCA (Principal Component Analysis)
- Model Development and Evaluation
- Regression Analysis (Predicting IMDb Scores)
- Model Performance Metrics (RMSE, R-Squared)
- Feature Importance Analysis

## Usage
--- 
If you would like to run this project yourself, please do the following:

Clone this repository - Make sure you have all the correct packages + their latest versions installed as specified in the requirements file.

## Contact Details
---
If you have any questions or suggestions, feel free to reach out. Contributions to this project are welcomed.


