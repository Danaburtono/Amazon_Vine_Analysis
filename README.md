# Amazon_Vine_Analysis

## Overview of the analysis:

The purpose of this analysis is to explore the world of Big Data by using Amazon Web Services (AWS) Management Console to store and create a cloud-based relational database service (RDS). We also utilized PGAdmin4 and Google Colab Notebook to work together to analyze Amazon reviews for digital videogames. We were able to extract, transform, and load large quantities of data quickly and efficently and come to conclusions about whether the data may or may not have been inappropiately influenced by paid reviewers. 

## Results:

- How many Vine reviews and non-Vine reviews were there?<br/>
  Vine reviews: 0<br/>
  Non-Vine reviews: 1685<br/>
  
  <img width="284" alt="Screen Shot 2022-10-09 at 8 43 43 PM" src="https://user-images.githubusercontent.com/107026442/194800458-40879fa7-fe90-456a-8c2a-51f3fdce9432.png">
  
  <img width="359" alt="Screen Shot 2022-10-09 at 8 43 35 PM" src="https://user-images.githubusercontent.com/107026442/194800514-73553b5a-0682-4793-8af8-43a253d508d3.png">
  

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?<br/>
  Vine reviews: 0<br/>
  Non-Vine reviews: 631<br/>
  
  <img width="639" alt="Screen Shot 2022-10-09 at 9 47 49 PM" src="https://user-images.githubusercontent.com/107026442/194800683-1ef8e451-6300-431c-8e9f-648df33bd9f6.png">


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?<br/>
  Percentage of 5-star reviews for paid Vine program was: 0%<br/>
  Percentage of 5-star reviews for unpaid Vine program was: 37.448071%<br/>
  
  <img width="677" alt="Screen Shot 2022-10-09 at 9 48 20 PM" src="https://user-images.githubusercontent.com/107026442/194800695-3e874910-b78c-4d5f-91ff-ebf21b39b005.png">

  

## Summary: 

Due to the nature of the category Digital Video Games, I believe it somewhat flawed data. Most people are not buying digital video games on Amazons platform they would more likely go to their Consoles online marketplace. Most reviews do no have more than a few likes and have little to no "helpful" attribute assigned. After some digging, I found that there are overwhelmingly negative reviews for Amazon digital video games because it can be incredibly hard to download, no customer service, sometimes won't download at all. The positive reviews that are provided typically focus on the quality of the games, however even a good review stated something like "great game shouldnt have bought it on Amazon".

One reviewer said, "Download process came through email and was multi step through a convoluted process. Customer service was awful when I called them about this as it was a present for my husband. You get the same thing you could on Game Pass. Don’t buy here." 

I believe the criteria used to analyze the data was inapporiate. A service that cannot deliever the thing they promised inheritly cannot retain 5 star rating so it makes sense that our results showed a 0%. We would have expected the paid Vine program to recuite a higher percentage of 5-star reviews. My conclusion is that is data has no paid bias. If I could add one additional analysis it would be to reduce the helpful criteria to to 4-5 and the like criteria to 4-5. This analysis would have been good to implement NLP to determine a sentiment analysis. 
