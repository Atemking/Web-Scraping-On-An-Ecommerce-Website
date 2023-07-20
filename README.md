# Web Scraping On An Ecommerce Website

We are to scrapped data from an ecommerce website, that we can use for any data analysis,data science or machine learning project.
Before we scrapp data from this website , we have to install and import some few libraries.

# Project Steps:

## STEP 1:
In this project , we use the following libraries below to perform extraction on **Amazon Platform**

* Request
* BeautifulSoup


## STEP 2:

The following extensions above were been downloaded and install. after that we imported them on jupyter lab
using the following commands below. 

* import  urrlib
* from bs4 import BeautifulSoup


## STEP 3:

Once we had all our required libraries ready to be use in **Google colab** We the analyse the website to be 
scrapped been called [books](http://books.toscrape.com/). 

We start by analyzing the website link format. after analysing the format in which the links of each page are 
been created , we then create a variable to contain  and store all the links of the number of pages which we are 
interested in scrapping . 

## STEP 4:
After storing the all the links of pages to be scrapped in variable(probably a list), we proceed to analyse the 
web content of the various pages to be scrapped. in this project we focus mainly on getting the price , reviews 
and the review counts.
Note that all this information can be gotten after analyzing the html content of the site. 

## STEP 5:

Once we have analyse [books](http://books.toscrape.com/) and are been able to get  the various information which we need above , we then proceed to create a function which contains all the codes to scrap the [books](http://books.toscrape.com/) for a give number of page. 

## STEP 6:

After creating the generic function,  the data is been scrapped from the site and all the information gotten after scrapping 
is been stored in a variable which is later on converted into a pandas dataframe for further analyses. 

## STEP 7:

The information which is been stored into the dataframe is been clean and analyse.
From the analyses certain observations where been derived as listed below. 

* It is noticed that products which cost less had higher number of rating.
* Also a product with higher number of rating means people were buying it allot . 


# Insights:

It was quite difficult getting some of the libraries install for scrapping and also getting the required information as 
demanded by the project was not quite easy too . 

# Future Work:

I am working on extracting more data from [books](http://books.toscrape.com/) to perform more analyses on it to see how the prices will affect how long
the products stays on the platform without them running out of stock. 

















































