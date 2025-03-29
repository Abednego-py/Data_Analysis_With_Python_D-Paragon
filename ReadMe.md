# Supermarket Data Analysis Project



## Overview

`Problem Statement`

Company XYZ owns a supermarket chain across the country. Each major branch located in 3 cities across the country recorded sales information for 3 months, to help the company understand sales trends and determine its growth, as the rise of supermarkets competition is seen.

`Objective`

Using the datasets for the three branches - Lagos, Abuja and PH, we would try to answer questions that would help us understand sales trends and determine how well the comapny is growing. 

`Approach`

To achieve this, we are going to approach the analysis using the CRISP-DM (Cross-Industry Standard Process for Data Mining) Framework  

- Properly understand the business and data

- Prepare the data for analysis

-  Answer questions to help us achieve our objectives

- Draw conclusions

- Prepare a summary 

## Data 

The data folder contains datasets from three different branches; Lagos, Abuja and Port Harcourt. Each data file from the branches contains the same attribute information and see below the attribute description.  

`Invoice ID`: Customer Identification number

`Branch`: Supermarket Branch across the country (A, B, C)
A - Lagos Branch
B - Abuja Branch
C - Port Harcourt Branch

`City`: Supermarket Location

`Customer Type`: Type of customers, Members - Returning customer with membership card, Normal - Customer without membership (could be returning, first-time or walk-in customer)

`Gender`: Customer Gender Information

`Product line`: Product categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel

`Unit Price`: Price of each product in Naira

`Quantity`: Number of products purchased by customer

`Tax`: 5% tax fee for customer buying

`Total`: Total price including tax

`Date`: Date of purchase (Supermarket Record available from January 2019 to March 2019)

`Time`: Purchase time (Supermarket Hours - 10am to 9pm)

`Payment`: Payment used by customer for purchase (3 methods are available – Cash, Card and Epay)

`COGS`: Cost of goods sold

`Gross margin percentage`: Gross margin percentage

`Gross income`: Gross income

`Rating`: Customer Satisfaction rating on their overall shopping experience (On a scale of 1 to 10) 


# Insights

The following insights were drawn from analyzing the data:

- Portharcourt branch is generating more income than Lagos then Abuja. There isn't much difference in the revenue generation for the 3 branches.

- In order of usage, the most popular payment methods are Epay, Cash then Card

- In terms of quantity of items bought, electronic accessories and Food beverages come tops where health and beauty items are least purchased

- Over the course of the 3 month period, the highest sales was recorded in January, there was a decline in February and pick up in March

- A further drill down on sales trend indicated that :

  - In the month of January,  Wednesdays, Thursdays and Tuesday are when we generate most sales
 
  - For February, it is  Friday, Sunday and Tuesday. It is obvious that compared to January, the sales were not steady in February.
 
  -  For March, Saturdays were far better in sales compared to the rest, then Sunday and Friday


- In understading the impact of customer type on product line, it was found that for the following product categories : Sports and travel, health and lifestyle and Electronic accessories, normal customers generate more sales.

  For the rest , member customers generate more sales. This is more significant for the health and beauty category and less significant for fashion accessories category 

- Overall for the course of the 3 month period, PH has the highest rating then Lagos and Abuja.

- A futher drill down on rating shows that there are more medium ratings (52%) then high (31%) and low (17%) and PH has the   highest low rating (48) while Abuja has the highest low rating (66)

 The ratings have been categorised using the keys below:

     < 5 : Low
     5 <=> 8 : Medium 
     > 8 : High

- In understanding payment channels used in each branch, it was found that:

    - All 3 payment channels are used almost equally in Lagos

    - Card is the most popular method in Abuja then Cash and Epay

    - In PH, it is Epay then cash and card.

- For comparing product line to gender, it was discovered that :

    - More females purchase items from these product lines: home and lifestyle, fashion accessories and food and beverages.

    - More males purchase items in the categories: Sport and travel and health and beauty.

- Overall, the busiest hours are 7pm , 1pm and 3pm respectively

- A further drill down per location:
    - In Abuja, 7pm, 1pm and 2pm are the busiest. 7pm is an extremely busy time

    - In Lagos, 3pm, 10am and 11am are the busiest

    - In PH, 7pm , 1pm and 10am are the busiest

# Conclusion, Recommendation and Future Work

The objective of the analysis was to help us understand sales trends and determine how well the comapny is growing. Here is the conclusion of what was found: 

-  Since a lot of our customers prefer using Epay to make payment in PH, we should find ways to optimize this channel. In Abuja, we should look for more ways to accept card payment. 

- We need to ensure that we have a good inventory of the following product categories: electronic accessories and food beverages

- There seems to be a direct correlation between service delivery(Rating) and income generation. P.H is the branch with the lowest low ratings and they generate the highest income. This is followed by Lagos and Abuja.

- Abuja seems to be contributing more to the overall low rating and there is need to address why customers are unhappy with service delivery in that branch. 

- We need to ensure that we have enough manpower to handle requests during the busiest time - 7pm and 1pm for P.H and Abuja; 3pm and 10am for Lagos.

- We need to investigate the decline from January to February

- We need to investigate what we did well to generate so much revenue in January.


# Executive Summary.

Link to executive summary : [See Executive Summary](https://docs.google.com/document/d/19mqwFIrYKSpB7egBSwuY2NBheIBDlgnxi5NhJjvN9Sc/edit?usp=sharing)
