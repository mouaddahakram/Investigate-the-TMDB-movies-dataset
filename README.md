
# Project: Investigate the TMDB movies dataset:

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#eda">Exploratory Data Analysis</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>

<a id='intro'></a>
## Introduction

In this project, we will explore the data gathered from Kaggle (the cleaned version provided by Udacity). The data has information about more than 10000 movies, the number of votes, budget, and revenue of the movies, director and cast of the movies,..etc. The goal of this project is to get an idea of what factors can play a role in making movies more profitable and likable from the viewers. During my EDA I tried to answer the question below :
 
> * **Which type of movies is the most-watched from year to year?**
> * **What types of movies are associated with a higher rating?**
> * **What kind of properties are associated with movies that have high revenue? How these properties are affecting the revenue of the movies?**
> * **Which actors had made the most number of appearances?**


<a id='wrangling'></a>
## Data Wrangling

In this section, we will focus on importing the data, assess it and clean it, the goal is to make the best of our data to get it ready for the next phase (EDA). Cleaning the data will include, keeping only the columns needed for our analysis, dealing with the missing values, correcting the names of the columns, and getting rid of the duplicated values.

<a id='eda'></a>
## Exploratory Data Analysis

In this section we will try to answer our questions by processing our cleaned data and using matplotlib and seaborn libraries to visualize the results.

<a id='conclusions'></a>
## Conclusions

> As summary of our analysis on the dataset collected between 1960 and 2015 :

> * **Drama** has been the most watched type of movies 
> * **The Shawshank Redemption** is the highest rated movie 
> * **Robert De Niro** has the highest number of appearances in movies 
> * **Action** and **Comedy** tend to be the most profitable genre of movies
> * **Votes** don't affect the profitability of the movie

>The findings mentioned above are basic to understand what factors can play major roles in either recommending a movie or anticipating if a movie will be profitable or not, in addition to other analytics that required statistical tests. However, some limitations were observed, we can mention the lack of information about certain columns,  like 'popularity' that we don't how it is calculated neither what is the scale; knowing such as information would help us to get more accurate results and make better conclusions.


**NOTE**

***You may find it frustrating scrolling down in 2 parts of the code that I chose to print the list of the Actors and another list of Movies types, I apologize for the inconvenience, you can jump to the PDF version that is limited to one page for the print section.***

