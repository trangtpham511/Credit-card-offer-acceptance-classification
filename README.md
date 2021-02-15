# Credit-card-offer-acceptance-classification

## General information

#### Situation:

- The bank wants to understand the demographics and other characteristics of its customers that accept a credit card offer and that do not accept a credit card.

- The bank designs a focused marketing study, with 18,000 current bank customers and use existing demographic data that is already available on each customer.

#### Objectives:

- Build a model that will provide insight into why some bank customers accept credit card offers.
- There are also other potential areas of opportunities that the bank wants to understand from the data.
- Help the senior management to understand their customers better.

## Techniques
- The 'creditcardmarketing.csv' file will first be imported into MySQL WorkBench, where we will create correct headers for each columns (the original file does not contain headers). Further data exploration will be performed here before uploading into Python

- The credit card offer acceptance prediction requires classification model. We will use Logistic Regression, K-Neighbors Classification and Decision Tree to choose which model will give the best prediction. Our particular project focus on maximizing Kappa score due to data's high imbalance and maximizing recall score to make sure the bank do not miss out on offering the customer that will accept the offer. 

- Data vizualiztion is performed using Tableau. 
https://public.tableau.com/profile/trang.thu.pham#!/vizhome/project_classification_16130539698300/Sheet50

## Recommendations

- We recommend to gather more data concerning transactional behavior of the customers, to be able to do a better prediction on one of the objectives, the credit rating, since from the current data the customers which have a low credit rating are most likely to accept the offer
- We recommend to focus on the customers that have a high probability to accept the credit card offer with the characteristics of owning their home, have a larger household of 3 and got less than two credit cards held
- Based on the current data the best way to offer the credit card is by postcard, but since there might be better options at this moment, ie email (newsletters) and social media something to consider as well
- Another interesting criteria to focus on would be customers with no overdraft protection, who are most likely to accept the offer
