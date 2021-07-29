# UCB-Big_Data_AWS-A16

ETL and meta-analysis of Amazon Vine reviews on Music Instruments using AWS, postgresql, PySpark and Google Collab.

## Overview 

- **Aim** : To cary out a meta-analysis of Music Instruments on Amazon reviews. Analysing the review is a part of the Amazon Vine programme that the selected members of Amazon's reviewer community are compensated to review sample products. 
      - To determine if there are any bias towards favourable reviews from the paid Vine members 

- **Dataset** : Musical Instrucments is the dataset used for this analysis, 

- **ETL** : Using AWS, postresql and PySpark in Google colab

- **Data Analysis** : Using PySpark in Google colab

## Results 

- Filtered the available review down to just ones with more than 20 votes and more than 50% helpful.

![Review_more_than_20_50%_helpful](https://user-images.githubusercontent.com/70616488/127565224-6f108043-f52b-49b4-9457-90b7e3fa4fcb.PNG)

- Out of 14533 reviews, 60 (0.41%) are from paid Vine members and 14473 (99.6%) are from unpaid Vine members. 

![Paid_Unpaid_Review](https://user-images.githubusercontent.com/70616488/127565261-978fc33b-40b8-4b52-833b-2548a6e19878.PNG)

- Out of 8244 five-star review, 34 (0.412%) are paid members and 6263 (99.59%) are unpaid members. 

![5_star_paid_unpaid_review](https://user-images.githubusercontent.com/70616488/127565306-bb9413de-458d-4384-a4a1-329826a18aca.PNG)

- Out of 60 paid members review, 34 of them are five-star. 

- Out of 14473 of reviews from unpaid members, 43.27% of them are five-star.

- Out of 8244 five-star review, 75.97% of them are from unpaid members. 

![5_star_unpaid_review_percentage](https://user-images.githubusercontent.com/70616488/127565341-4928addf-235d-4b28-bc89-19fab85178f4.PNG)


## Summary 

From the results and calculations, it indicates that whether a Vine member or not does not have the bias for the favourable reviews. If the Vine reviews might show a tendency towards being more critical in their reviews in the future, further examination required by looking at the distribution of all star-levels across paid and unpaid reviews. The same meta-analysis should be conducted across a few different product catagories to confirm there's no tendency between paid and unpaid Vine members for the reviews. 
