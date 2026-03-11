Assignment 5.1: Will the Customer Accept the Coupon?

Overview

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under 20), coffee houses, carry out & take away, bar, and more expensive restaurants (
20 - $50).
Following EDA steps were followed:

1.	Understanding the dataset provided by the retail Business 
2.	Cleaning steps : missing values, outliers, data corrections 
3.	Exploration of customer demographics and spending patterns
4.	Comparison of income, product category, and transaction amounts 
5.	Business insights that leadership can act upon 

Files : 
data/coupons.csv -> Original dataset
images -> plots and visualizations
prompt.ipnyb -> Data analysis - Notebook

Summary: Characteristics of Coffee House Coupon Acceptors
Based on the analysis of 'Coffee House' coupons, the following characteristics are observed in passengers most likely to accept these coupons:

High Frequency Coffee Drinkers: Drivers who visit coffee houses 'more than 3' times a month show a significantly higher acceptance rate (approximately 68%) compared to those who visit '3 or fewer' times (approximately 45%).

Younger, Frequent Coffee Drinkers: Drivers who are under 30 years old AND visit coffee houses more than 3 times a month have an even higher acceptance rate (approximately 69%), demonstrating a strong preference in this demographic segment.

No Kid Passengers, Frequent Coffee Drinkers: Drivers who visit coffee houses more than 3 times a month AND do not have kid passengers also exhibit a higher acceptance rate (approximately 67%). This suggests that the presence of children might influence the decision, or that those without children might have more flexibility to use the coupon.

Time of Day: For frequent coffee house visitors ('more than 3' times a month), coupon acceptance is notably high during 10 AM (approximately 82%) and 2 PM (approximately 71%). This indicates that these times are prime opportunities for targeting this group. Conversely, acceptance rates are lower in the evenings (6 PM, 10 PM) for both frequent and infrequent visitors.


**Summary:**
**Data Analysis Key Findings**
The overall acceptance rate for 'Coffee House' coupons is 50%.
Drivers who visit coffee houses more than 3 times a month have a significantly higher acceptance rate (68%) compared to those who visit 3 or fewer times (45%).
Drivers under 30 years old who visit coffee houses more than 3 times a month show an even higher acceptance rate of 69%. This is a 21 percentage point increase compared to all other drivers (48%).
Drivers who visit coffee houses more than 3 times a month and do not have kid passengers also exhibit a higher acceptance rate of 67%. This is a 22 percentage point increase compared to all other drivers (45%).
For frequent coffee house visitors (more than 3 times a month), coupon acceptance is highest at 10 AM (82%) and 2 PM (71%).
Insights or Next Steps
Target marketing efforts for 'Coffee House' coupons towards frequent coffee house visitors, especially those under 30 and without kid passengers, as they demonstrate the highest acceptance rates.
Optimize coupon distribution times to align with peak acceptance periods, specifically 10 AM and 2 PM, to maximize redemption rates among frequent coffee drinkers.

**Overall Hypothesis:** Passengers who are frequent coffee house visitors (more than 3 times a month), particularly those who are younger (under 30) and driving without children, are most inclined to accept 'Coffee House' coupons, especially during mid-morning and early afternoon hours.

**Insights or Next Steps**
Target marketing efforts for 'Coffee House' coupons towards frequent coffee house visitors, especially those under 30 and without kid passengers, as they demonstrate the highest acceptance rates.
Optimize coupon distribution times to align with peak acceptance periods, specifically 10 AM and 2 PM, to maximize redemption rates among frequent coffee drinkers.



