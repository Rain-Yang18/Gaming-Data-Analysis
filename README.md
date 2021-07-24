# Pandas-challenge - Heroes of Pymoli

## Introduction

This challenge is analysing the data for a fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. The task is to generate a report that breaks down the game's purchasing data into meaningful insights.

### Data
* [Heroes of Pymoli](HeroesOfPymoli/04_Pandas_purchase_data.csv)

### Report
The report includes the following:
* Player Count
    * Total Number of Players

* Purchasing Analysis (Total)
    * Number of Unique Items
    * Average Purchase Price
    * Total Number of Purchases
    * Total Revenue

* Gender Demographics
    * Percentage and Count of Male Players
    * Percentage and Count of Female Players
    * Percentage and Count of Other / Non-Disclosed

* Purchasing Analysis (Gender)
    * The below each broken by gender
      * Purchase Count
      * Average Purchase Price
      * Total Purchase Value
      * Average Purchase Total per Person by Gender

* Age Demographics
    * The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
      * Purchase Count
      * Average Purchase Price
      * Total Purchase Value
      * Average Purchase Total per Person by Age Group

* Top Spenders
    * Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
      * SN
      * Purchase Count
      * Average Purchase Price
      * Total Purchase Value

* Most Popular Items
    * Identify the 5 most popular items by purchase count, then list (in a table):
      * Item ID
      * Item Name
      * Purchase Count
      * Item Price
      * Total Purchase Value

* Most Profitable Items
    * Identify the 5 most profitable items by total purchase value, then list (in a table):
      * Item ID
      * Item Name
      * Purchase Count
      * Item Price
      * Total Purchase Value

### Insights
1.    Majority (84%) players are male players. However, when we look at their purchasing pattern, we could see despite male players are making more purchases, female players are having a slightly higher average purchase price and average total purchase value per person.
2.    The target age group for this game is age 15-29, around 76% of the players are within this age group. The highlight is the players between the age of 20-24, they have the highest total purchase value. 
3.    The most popular item in the game is the ‘Final Critic’, which has been purchased by 13 times. This item does not have the highest item price, however, with the highest purchase count it became the most profitable item.


### Copyright

Trilogy Education Services © 2021. All Rights Reserved.
