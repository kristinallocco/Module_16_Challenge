# Amazon Vine Review Analysis
03 Oct 2021

## Overview
The purpose of this analysis was to utilize PySpark in an effort to analyze data obtained from Amazon reviews written by members of the paid Amazon Vine program, which is a service that allows vendors to receive reviews on their product; video games were selected as the product in question. PySpark was first used to perform the ETL process to extract and transform, connect to AWS, and then the transformed data was loaded into pgAdmin. Following this, PySpark was again used to determine if there is bias toward favorable reviews from Vine members. 

## Results
- How many Vine reviews and non-Vine reviews were there?
  - There were a total of 40565 reviews on the products. 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - There were 48 5-star Vine reviews and 15663 5-star non-Vine reviews
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - Overall, 38.7% of the Vine reviews were 5-stars. Additionally, 38.2% of the 5-star reviews were Vine, and 38.9% of the 5-star reviews were non-Vine.

<img width="550" alt="Screen Shot 2021-10-03 at 10 25 41 PM" src="https://user-images.githubusercontent.com/85713470/135784789-0e21532e-cbbb-46f5-8f46-837db5153b22.png">


<img width="550" alt="Screen Shot 2021-10-03 at 10 25 50 PM" src="https://user-images.githubusercontent.com/85713470/135784774-0959d74d-a623-45cd-9066-3fd2b1944151.png">

## Summary
Although there were significantly fewer Vine reviews than non-Vine, both had a very similar 5-star rating percentages at 38.2% and 38.9%.
