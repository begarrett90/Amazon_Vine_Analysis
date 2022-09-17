# Amazon_Vine_Analysis

## Purpose
The purpose of this project was to see if there is a bias toward favorable reviews from Amazon Vine members. The product set used to analyze this was based on furniture. 

## Results
 1. An Amazon Review data set was extracted as a DataFrame 
 2. Four dataframes were created from the extracted dataset: customer table, products table, reiew id table, and vine table
 
 <img width="185" alt="Mod 16 D1 customer table" src="https://user-images.githubusercontent.com/105942622/190870153-0ce86d4f-f8eb-48ef-a344-16a5907656be.png">

<img width="215" alt="Mod 16 D1 products table" src="https://user-images.githubusercontent.com/105942622/190870155-2209030d-9460-4196-9e39-c6961c833a08.png">

<img width="421" alt="Mod 16 d1 review id table" src="https://user-images.githubusercontent.com/105942622/190870170-50fb7e71-ea64-42bc-964f-86c45988b834.png">

<img width="488" alt="Mod 16 D1 vine table" src="https://user-images.githubusercontent.com/105942622/190870172-4a9fdecb-bcf6-42f6-9257-8bd6f453b091.png">

3. These tables were then uploaded into pgAdmin

<img width="194" alt="customers table" src="https://user-images.githubusercontent.com/105942622/190870277-6311e4d2-c6af-471c-b993-1f7d19f636cb.png">

<img width="173" alt="SQL Products query" src="https://user-images.githubusercontent.com/105942622/190870291-a41b335b-4fb1-479f-ae8b-ad051ef368b6.png">

<img width="416" alt="review_id query" src="https://user-images.githubusercontent.com/105942622/190870296-76b3fe7e-1746-4cd0-9c87-dd6a13f87d4f.png">

<img width="451" alt="vine table query" src="https://user-images.githubusercontent.com/105942622/190870298-174c4b00-79e8-4f26-a5ab-9d4cf0ff250f.png">

4. The vine table was then extracted as a csv file (vine_table.csv) and uploaded into Jupyter Notebook where using Pandas an analysis was performed to get the results listed below:

How many Vine reviews and non-Vine reviews were there?
- Vine Reviews: 136
- Non-Vine: 18019

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine: 74
- Non-Vine: 8482

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine: 54.5%
- Non-Vine: 47%

## Summary

There is a slight bias of Vine reviews to leave a 5 star rating as compared to nonVine reviews, however it was small only 7.5% higher. Further analysis on other product datasets would be needed to see if there is a pattern of Vine reviews being more likely to leave higher and 5 star ratings as compared to nonVine reviews. 
