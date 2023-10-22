# Fraudulent-Analysis-on-BITCOIN-and-AMAZON-Data
Detecting Fraudulent Users in the Bitcoin and Amazon Networks:  An SNA-Based Approach using Fairness and Goodness

For example, if a user consistently rates a 5 star-deserving product as 5 star and 1 star deserving product as 1-star, then the user is fair. And a high quality (good) product gets  high ratings from highly fair users. Whereas if a user rates a 1-star deserving products  5-star and a 5-star deserving product as 1-star then the user is not fair. 

**DATASET DESCRIPTION - AMAZON**
Each line has one rating with the following format:
**Reviewer ID, Asin, Overall.**
1. Reviewer ID: Id of the reviewer.
2. Asin: ID of the product.
3. Overall: rating of the product.

**DATASET DESCRIPTION - BITCOIN**
Each line has one rating with the following format: 
**SOURCE, TARGET, RATING, TIME**
1. SOURCE: node id of source, i.e., rater 
2. TARGET: node id of target, i.e., ratee 
3. RATING: the source’s rating for the target, ranging from -10 to +10 in steps of 1 
4. TIME: the time of the rating, measured as seconds since Epoch.
