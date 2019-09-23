# GoodReads-data-analysis

# Predicting Book Rating on GoodReads.com

## Question:
I wondered whether Ratings (the number of stars, from 1-5) were based on any quantifiable data. I looked at Ratings compared to: 
- length of title (number of words in title)
- total number of reviews
- number of pages in book

## Conclusion:
I did not find a correlation between Ratings and any of the above factors.

### Dataset:
The dataset I used was pulled from Kaggle. The original csv had 13,719 rows.

### Data Cleaning:

Columns:
I removed columns for ISBN numbers (both types), renamed columns so there would be no spaces, and removed a column named "Unnamed" that had only NaN

Rows:
I removed rows that had words I felt were not helpful for getting to an answer, or indicated a type of book that would not be relevant.
After creating the scatterplots, I also removed rows with values that were significant outliers.
