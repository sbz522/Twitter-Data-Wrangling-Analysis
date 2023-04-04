# Twitter-Data-Wrangling-Analysis

WeRateDogs is a Twitter account that posts and rates pictures of dogs. These ratings often are not serious and have numerators that are greater than the denominators. In this analysis, I mostly focus on wrangling WeRateDogs's Twitter archive through August 1, 2017. Most of the necessary Twitter data has been provided by Udacity and includes information on each post, as well as details on each dog such as the name, rating, and stage (whether the dog is a doggo, floofer, pupper, or puppo). However, not all of the desired data is present in Udacity's dataset, so I also use the Twitter API to gather additional data.

# Overview
The goal of this project was to Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations, and specifically to:

  * Perform data wrangling (gathering, assessing and cleaning) on provided sources of data.
  * Store, analyze, and visualize the wrangle data.
  * Report on 1) data wrangling efforts and 
            2) data analyses and visualizations.

In the data wrangling process, I focus on original tweets by WeRateDogs that have ratings and images. At the end, I also provide a brief analysis using the cleaned data. In the analysis, I aim to answer the following questions:
  * What are the most popular dog breeds based on number of posts, interactions by Twitter users, and ratings?
  * Is there any correlation between WeRateDogs's ratings and the interactions by Twitter users?
