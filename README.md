# COVID-19 and Mental Health
<img src = './images/covid19.png' width = "800"></img>


## Contents

* [Executive Summary](#Executive-Summary)
* [Problem Statement](#Problem-Statement)
* [Process](#Process)
* [Conclusion and Suggestions](#Conclusion-and-Suggestions)
* [Data Dictionary](#Data-Dictionary)


## Executive Summary




## Problem Statement

As COVID is impacting our everyday lives and shaping our present and future the way we did not project. We as people are struggling with keeping up with daily decisions and tasks since we are experiencing something that we did not expect to happen - loneliness, feeling of isolation, stress of not being able to be alone
when needed, instability of finances, and etc. Because of this, I would like to find out what has been going on with our mental health pre/post pandemic. For this, I will perform sentiment analysis, as well as how the trend has shifted, use unsupervised learning to find unknown patterns in the data, and search for the features that could be useful for multi-class categorization.

## Process

* <font size = 4><b>Data Collection</b></font><br> 

* <b><font size = 4>Data Cleaning</font></b><br>

* <b><font size = 4>Feature Engineering</font></b><br>

* <b><font size = 4>Exploratory Data Analysis and Visualization</font></b><br>

<div id = 'header'>
  
</div>

* <b><font size = 4>Modeling</font></b><br>

* <b><font size = 4>Best Model</font></b><br>

<div id = 'header'>
  
</div>


## Conclusion and Suggestions



## Data Dictionary
|Dataset|Column|Data Format|Description|
|---	|---	|---	|---	|
|Final|subreddit|string|Which subreddit the post belongs to| 
|   	|author|string|Person who wrote the post| 
|   	|date|datetime|Date the post was written| 
|   	|post|string|Post (raw)| 
|   	|...|   	|   	| 
|   	|tfidf_words|float|Weighted value of vectorization by Tf-idf| 
|   	|...|   	|   	|
|   	|n_sentence|int|Number of sentences in the post| 
|   	|post_clean|string|Post after removing non-word items and lemmatizing| 
|   	|n_words|int|Number of words in the post| 
|   	|n_chars|int|Number of characters in the post|
|   	|ari|float|Automated Readability Index| 

## Directory

|__ Code<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [01-Creating DB.ipynb](./code/01CreatingDB.ipynb)  
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [02-Feature Engineering and Preprocessing.ipynb](./02FeatureEng.ipynb)  
|__ Data<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [dataset - combined all](./data/cleaned/combined.csv)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [dataset - final version](./data/cleaned/final.csv)<br>
|__ Images<br>
|__ [Presentation]<br>
|__ [README.md](./README.md)