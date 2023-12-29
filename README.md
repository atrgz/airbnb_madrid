# Analysis of AirBnB data in Madrid

## Table of contents
- [Installations](#installations)
- [Project Motivations](#project-motivations)
- [File Descriptions](#file-descriptions)
- [Licensing, Authors and Acknowledgments](#licensing-authors-and-acknowledgments)

## Installations
This project is written in Python 3.11.5 usign the following  libraries:
* numpy 1.24.3
* pandas 2.0.3
* matplotlib 3.7.2
* scikit-learn 1.3.0
* seaborn 0.12.2

## Project Motivations
This work is the result of the project for the **Introduction to Data Science** module of the [Data Scientist Nanodegree of Udacity](https://www.udacity.com/course/data-scientist-nanodegree--nd025?promo=year_end&coupon=SAVE40&utm_source=gsem_brand&utm_source=gsem_brand&utm_medium=ads_r&utm_medium=ads_r&utm_campaign=19167921312_c_individuals&utm_campaign=19167921312_c_individuals&utm_term=143524475679&utm_term=143524475679&utm_keyword=udacity%20data%20science_e&utm_keyword=udacity%20data%20science_e&gad_source=1&gclid=EAIaIQobChMImKz0y_e0gwMVfj4GAB1FgAEHEAAYASAAEgI-h_D_BwE).

The CRISP-DM approach is followed to achieve results:
### 1. Business Understanding and Data Understanding:
Following the recommendations of the module description, a dataset is chosen from AirBnB. In this particular case, the AirBnB scraped data for the city of Madrid with date 15<sup>th</sup> of December of 2023. The data can be found [here](http://insideairbnb.com/get-the-data/).

After reviewing the data, the project aims to answer three questions:
- How are the listings distributed?
- What factors influence the reviews?
- Can the price be predicted?

### 2. Data Preparation:
To have a better understanding of the data, a dictionary of the fields in the dataset can be found [here](https://docs.google.com/spreadsheets/d/1iWCNJcSutYqpULSQHlNyGInUvHg2BoUGoNRIGa6Szc4/edit#gid=1322284596).

The data preparation is an process that takes part along the entire project, as different dataset with different characteristics are needed to answer each question.

### 3. Data Modelling:
To answer the last question a linear model is used considering quantitative as well as categorical variables.

### 4. Result evaluation:
The model doesn't yield good results as only 5% of the test set is explained, as per the R squared value.

### 5. Deployment:
Not applicable in this particular case.

## File Descriptions
There is a Jupyter Notebook available in the repository. The Notebook has markdown cells to provide a better understanding of the code as well as to separate the different sections of the notebook.

## Licensing, Authors and Acknowledgments
This project has no specific license, but some of the functions as well as the general structure of the project is inspired in Josh Bernhard's project about a survey in Stack Overflow. This project can be found [here](https://github.com/jjrunner/stackoverflow/tree/master)