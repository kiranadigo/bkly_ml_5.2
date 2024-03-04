# Goal
The goal of this project is to determine the likelihood of whether a customer will accept a coupon given to them based on their demographics, their contextual attributes at the time the coupon is given, and the actual coupon group itself. I selected the coupon group of Restaurants with average expense of under $20 as this was one of the biggest groups of coupons given or offered. There is an opportunity to target the coupons to certain demographics and attributes to maximize the acceptance rate.
# Approach
I used a two-stage approach, first exploring the data by each attribute to try to narrow down to the biggest drivers. Then I explored the data using combinations of attributes to determine if there are any strong combinations of attributes that are more likely to cause a higher acceptance rate.
# Findings
There are several key findings:
- Cheaper restaurant (<$20) coupons are accepted at a far higher rate (71%) compared to more expensive restaurants (41%)
- It was obvious from the data and intuition that the acceptance rate of these coupons is far higher for drivers who frequented these types of restaurants in the first place
- It was counter intuitive that the major of the coupons for cheaper restaurants were offered despite the driver going in the opposite direction of the restaurant
- Even more counter intuitive that drivers accepted them in higher percentage despite being in the opposited direction
- Drivers under 30 years of age accept coupons for cheap restaurants only slightly more than people over age 30, indicating that age alone is not a big contributor the acceptance rate of these coupons
- Same for the income distribution, drivers earning under or over $50K were offered about the same number of coupons and they accepted similar percentage of coupons (around 70%)

On analyzing a much larger combination of attributes, there are a few categories of drivers that stood out as having both a high number of offers and a good acceptance rate. One of the key baselines we need to establish is - what is the target acceptance rate. For the sake of this exercise, I set it as 75%. 


