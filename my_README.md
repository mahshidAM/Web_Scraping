<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# API and Web Data Scraping
*[Mahshid AMIR MOAZAMI]*

*[Ironhack, Paris, 30 November 2020]*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The goal is collect database from a website, using web scraping methods, clean it and finally export database to csv,sql. 
For this project, I choose the recipe website cuisineaz(one of the most popular recipe website in France). 


## Workflow

Analyse SiteWeb : First step was parsing html code in the recipes page and find usefull information. 

Collect Data : Using css selector to detect exact information from html tags. 

Create DataFrame: Load urls and imports information to the dataframe using python libraries. 

Clean DataFrame : Find missed or incorrect data, clean dataframe.

Export Data : Export dataframe to .csv file and create an sqlschema export recipe dataframe.



## Organization
In repositoy of project you find:

- output(recipe.csv, recipe.sql)
- my_README.md
- recipe_scraping.ipynb.ipynb (project main)
- scraper.py
- functions.py
  

## Links 

[Repository](https://github.com/mahshidAM/data-ft-par-labs/tree/main/Projects/Week-3)  
[Slides](https://docs.google.com/presentation/d/106trxUFulapPUJL-i_yZJb2qCaAK1XrjUUM42ZMmHIg/edit#slide=id.gadcb3388d0_0_33)  
