# COVID-19 and Mental Health
<img src = './images/assets/covid19.png' width = "800"></img>


## Contents

* [Executive Summary](#Executive-Summary)
* [Problem Statement](#Problem-Statement)
* [Process](#Process)
* [Conclusion and Suggestions](#Conclusion-and-Suggestions)
* [Data Dictionary](#Data-Dictionary)


## Executive Summary

As COVID is impacting our everyday lives and shaping our present and future the way we did not project. We as people are struggling with keeping up with daily decisions and tasks since we are experiencing something that we did not expect to happen - loneliness, feeling of isolation, stress of not being able to be alone when needed, instability of finances, and etc. Because of this, I would like to find out what has been going on with our mental health pre/post pandemic. For this, I will use natural language processing to understand the impact of COVID19 on mental health, and create a model to predict suicidability from the reddit data.

## Problem Statement


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


## Citation
Low, Daniel M., Rumker, Laurie, Talker, Tanya, Torous, John, Cecchi, Guillermo, & Ghosh, Satrajit S. (2020). Reddit Mental Health Dataset (Version 01)
https://theconversation.com/covid-19-could-lead-to-an-epidemic-of-clinical-depression-and-the-health-care-system-isnt-ready-for-that-either-134528



## Data Dictionary
|Dataset|Column|Data Format|Data Option|Description|
|---	|---	|---	|---	|---   |
|Final|subreddit|string|    |Which subreddit the post belongs to| 
|   	|author|string|    |Person who wrote the post| 
|   	|date|datetime|January 1 to April 20, 2020|Date the post was written| 
|   	|post|string|    |Post (raw)| 
|       |covid_related|integer|0, 1 |Post contains COVID related words|
|       |suicidal|integer|0, 1 |Post contains suicide related words|
|       |alc_abuse|integer|0, 1 |Post contains alcohol related words|
|       |loneliness|integer|0, 1 |Post describes loneliness|
|       |stress|integer|0, 1 |Post expresses stress|
|       |n_words|integer|2 to 5854|Number of words in a post|
|       |n_sentences|integer|1 to 460|Number of sentences in a post|
|       |lemmatized|string|     |Lemmatized post with spaCy|


## Directory

|__ Code<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [01-Creating DB.ipynb](./code/01CreatingDB.ipynb)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [02-Feature Engineering and Preprocessing.ipynb](./code/02FeatureEng.ipynb)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [03-Exploratory Data Analysis.ipynb](./code/03EDA.ipynb)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [04-Modeling.ipynb](./code/04Modeling.ipynb)<br>
|__ Data (due to size, data has not been included in GitHub repository)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [dataset - combined all](./data/cleaned/combined.csv)<br>
|&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|__ [dataset - final version](./data/cleaned/final.csv)<br>
|__ Images<br>
|__ [Presentation]<br>
|__ [README.md](./README.md)