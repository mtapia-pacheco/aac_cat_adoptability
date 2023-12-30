# Ausin Animal Center Modeling

What neural networks can best predict how long a cat spends in the shelter? What factors affect their adoptability?


## Motivation

I adopted my first pet from a shelter, an adult cat, earlier this year after being told by many others that older cats oftentimes spend more time in shelters than their younger 
counterparts. This project serves as a tool to investigate whether or not the age of a cat affects its chances of adoption and to search for any other possible factors affecting 
their adoptability. 


## Method and results

After processing the data, I visualized several variable relationships in the data and performed k-means clustering to check if there were any underlying patterns in the data. 
Unfortunately, I was not able to find very insightful information, but I was able to learn a lot about neural networks. Using a feed forward neural network, I was able to 
achieve a lower mean absolute error than with a random forest. However, the model did not perform well on the testing data. Ultimately, I believe the problem I was trying to 
solve is too nuanced for the data that I had.


## Repository overview


data

├--   raw

   |     └──   * raw csv files from aac website
   
├--   preprocessed

   |     └──   * merged and processed csv files

scripts

├--   drafts

   |     └──   Shelter_cats_eda.py  # pythin script with initial draft

results

├--   Shelter_cats_eda.ipynb  # ipynb file containing all code for the models and notebook

├--   Shelter_cats_eda.html  # html version of notebook

├--   Shelter_cats_eda.pdf  # pdf version of notebook

└──   models

   |     └──   * several models saved in .sav files

README.md


## More resources

* Link to the data set can be found [here](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238/about_data).
* This article by AnalyticsSteps helped me understand the differences between common neural networks. A link to the article can be found [here](https://www.analyticssteps.com/blogs/8-applications-neural-networks).
* This article on LinkedIn helped a lot in understanding how to construct my neural networks. A link to it can be found [here](https://www.linkedin.com/advice/1/how-do-you-design-architecture-number).

## About

I am the sole contributor to this repository.
