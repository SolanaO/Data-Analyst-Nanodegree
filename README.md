# Data Analyst Nanodegree Projects

Short descriptions and links to the reports for the eight projects which were part of a two terms nanodegree in data analysis with [Udacity](https://www.udacity.com/) (October 2017 - June 2018). The goals of the program is to learn how to organize data, uncover patterns and insights, draw meaningful conclusions, and clearly communicate critical findings. The work is performed in Python, R, SQL and Tableau. The presentations are written in Anaconda's Jupyter Notebook and in RStudio.

## Explore Weather Trends

This project presents an analysis of local and global temperatures for a period of more than 250 years. The global temperatures trends are compared with local trends for Columbus (Ohio, US) and two other cities: Madrid (Spain) and Helsinki (Finland). 

_This presentation is written in Jupyter Notebook, on a Windows 7 Professional system. The basic steps of data wrangling were performed using Google sheets._

[Link: Project1.Term1](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T1P1.Explore_Weather_Trends.html)

## 2016 US Bike Share Activity Snapshot
An exploratory analysis on data from [Motivate](https://www.motivateco.com/), a bike-share system provider for many major cities in the United States is performed. The system usage between three large cities: New York City, Chicago, and Washington (DC) are compared. The differences within each system for those users that are registered, regular users and those users that are short-term, casual users are also analysed.

_The project is completely done in Jupyter Notebook, using Python 3 and Matplotlib for visualizations. A notebook kernel is provided by Udacity and it has the information required for the completion of the project. It also contains questions and several blocks of code that guide the analysis of the data._

[Link: Project2.Term1](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T1P2.Bike_Share_Analysis.html)

## Investigate the TMDb movie dataset

Choose one of Udacity's curated datasets and investigate it using NumPy and Pandas. Complete the entire data analysis process, start by posing a question and finish by sharing the findings.

The dataset analysed here contains information about 10,000 movies collected from The Movie Database [TMDb](https://www.kaggle.com/tmdb) on Kaggle. It is investigated how various factors, such as budget, release time, genre, influence the revenue and the ratings of the movie. The dataset is assessed, cleaned and formatted. Exploratory data analysis is performed and visualizations are constructed. 

_The work is done in Jupyter Notebook, using a kernel provided by Udacity. The code is written in Python 3, using Pandas and NumPy._

[Link: Project3.Term1](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T1P3.Investigate_A_Dataset.html)

## Analyse Experiment Results

A dataset reflecting the results of an A/B test run by an e-commerce website is provided. In addition, a Jupyter Notebook containing various questions and required steps is also provided by Udacity. Using statistical techniques, questions about the data are answered. The goal is to determine if the company should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

_The code is written in Python 3, using Pandas and NumPy. The visualizations are created with Matplotlib._

[Link: Project4.Term1](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T1P4.Analyze_AB_Test_Results.html)

## Test a Perceptual Phenomenon

In this project, descriptive statistics and statistical tests are used to analyse the Stroop effect, a classic result of experimental psychology. Statistical inference is used  to draw a conclusion based on the results.

_The work is presented in a Jupyter Notebook, using Python and in particular Pandas, NumPy and selected packages from SciPy. The visualizations are created with Matplotlib._

[Link: Project1.Term2](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P1.Test_A_Perceptual_Phenomenon.html)

## Explore and Summarize Data: Red Wines Analysis

Using R and exploratory data analysis techniques a selected dataset is examinated for distributions, outliers and anomalies. The dataset contains information about red “Vinho Verde”" wine samples, from the north of Portugal. The goal is to determine which physicochemical attributes are relevant to the quality of the wine. There are 1599 samples of wine and 13 attributes for each sample. There are 11 variables based on physicochemical tests and the remaining one is quality.

_The project is written as Markdown document in RStudio, the analysis is performed in R._

[Link: Project2.Term2](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P2.Explore_A_Dataset.html)

## Wrangle and Analyse Data

Gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. Showcase the wrangling efforts through analyses and visualizations.

The dataset that is wrangled is an enhanced Twitter archive, provided by Udacity, of the user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. This dataset contains basic tweet data for more than 2000 tweets. The tweet text was used to extract ratings, dog names and dog stages. This file was downloaded manually from Udacity's website. 

The Twitter archive is enriched with two more datasets, described below. First with data obtained by query Twitter API, using Python's Tweepy library. This contains each tweet's retweet count and favorite ("like") count. Second with results obtained by running a neural network on the Twitter archive in order to predict what breed of dog is present in each tweet. The file is hosted on Udacity's servers and it was downloaded programmatically using the Requests library. 

The file [wrangle_report](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P3.Data_Wrangling/wrangle_report.html) describes in detail the wrangling efforts which are contained in the Jupyter notebook [wrangle_act](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P3.Data_Wrangling/wrangle_act.html). These are performed in Python 3, using Pandas and NumPy. The file [act_report.pdf](https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P3.Data_Wrangling/act_report.pdf) communicates the insights and displays the visualizations produced from the wrangled data.

## Create a Tableau Story - PISA 2012

In this project, a data visualization, using Tableau, from a data set that tells a story or highlights
trends or patterns in the data is created. The reflects the theory and practice of data
visualization, harnessing visual encodings and design principles for effective communication.

PISA is an international survey of students' skills and knowledge in reading, mathematics and science as they approach the end of compulsory education. In 2012 around half million students from more than 60 countries took this complex set of tests. In this report, PISA 2012 will be used to investigate the differences in achievement in mathematics tests based on location, gender and student attitudes.

The design of the Story is based on two factors: the main message/idea of the story (as described in the summary) and the possible audience for the presentation. It is assumed that the audience has some basic statistical knowledge and some interest or experience with math education.

After an initial description of the context, it is emphasized how certain metrics (such as math proficiency scores, indices that measure attitude towards math) differ with gender and location. The main measure to work with is the math proficiency score. In order to avoid information overload, only three indices are chosen from the long list of options which measure various attitudes towards math. These are math anxiety, math interest and math intentions. Maps with highlighting options and bubble graphs are used to give a visual understanding on how the variables are changing with location.

The PISA testing process is quite complex, the literature is extensive and it is the author's opinion that some specific information has to accompany the visualizations. This includes details on the mathematics proficiency levels and on how several mathematics indices are computed. This information is inserted as text boxes in dashboards. To enhance the visual appearance of the Story various types of graphs are used, the gender is color coded and filters are provided to the reader. Numerical details are included in tooltips.

Two types of numerical information are used, one that is based on percentages and the second that is based on actual counts. In the author's opinion alternating between the two approaches will encourage a conversation on how various countries participate in the survey, how the data is distributed worldwide and on genders and how statistically accurate this information is. For clarity and conciseness some of the variables and abbreviations are renamed, the tooltips and the axes names are edited.

_The data cleaning and preparation is done in Python 3, the results are comprised in a Jupyter Notebook:

  [PISA_dataWrangle](http://htmlpreview.github.io/?https://github.com/SolanaO/dand_udacity/blob/master/dand.T2P4.Tableau_Story.html)

_The results and the analysis are visually presented in a Tableau story:
  
  [Link to Tableau Story]()


