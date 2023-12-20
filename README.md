
# Rose's Capstone (name TBD) 
## 	Executive Summary
My capstone will investigate if there are any patterns in ingredients used in top rated recipes from All Recipes and the Food Network. We will look at recipes scraped from both sources and will look at which ingredients tend to appear in high rated recipes and which ingredients appear in lower rated recipes. 

## Motivation

Cooking is a life long passion of mine. I've always enjoyed exploring different flavors and techniques and strongly believe that food is an excellent way to learn more about ourselves, our past and our communities. 

## Data Question

Is there a pattern in which ingredients appear in top-rated recipes?

## Primary Data Sources
AllRecipes.com
FoodNetwork.com

### Secondary Data Source
[Generic Foods CSV](https://data.world/alexandra/generic-food-database/workspace/file?filename=generic-food.csv) 


## Challenges
Webscraping both websites was a challenge! I implemented BeautifulSoup and Selenium Web Driver to be able to grab the data I needed from each website. 

Another challenge was in the cleaning of the data. I had to adjust my code to ensure that recipes were being matched with the correct ingredients. I also had to create a relationship between my scraped recipes and my secondary data of generic foods to be able to see how often ingredients appeared by recipe. 

## Technologies Used
BeautifulSoup and Selenium Web Driver
Python in Jupyter Notebooks
PostgreSQL 
Tableau