# DRIVING-COUPONS---Practical Application 

GOAL: Utilize data exploratory techniques to answer a business question, "Will a customer accept a coupon"? Distinguish between customers who accepted a driving coupon versus those that did not.

DATA: This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20-$50) 

5 Different Types of Coupons:
1. Less expensive restaurant (<$20)
2. Coffee Houses
3. Carry out & take home
4. Bar
5. More expensive restaurants ($20-$50)

In this analysis, I've explored acceptance rates of Coffee Houses and Bar coupons. Coffee Houses coupons is the most frequently distributed driver coupon, approximatelt 32% of the total coupons and Bar coupons are second to the lowest less frequently distributed coupon, approximately 18% of the total coupons distributed. 


Key Findings on the acceptance of Bar Coupons:

1. Customers who goes to bars more frequently are less likely to accept bar coupons than customers who goes to the bar less. If they like to go to bars, they will go regardless of having a coupon. On the other hand, less frequent bar goers are more likely to accept the coupon, as the 81% acceptance rate shows. They do not like going to bar too much and to spend money there is not a priority for them, so bar coupons might be a good incentive. 

2. Customers going to bar more than once a month and over age of 25 are likely to accept bar coupons. This age group itself already assume the beginning of drinking stage and high social engagements. This group of customers  are either just started to go to bars or can also be the customers who have been going to bars more frequently. 


3. Customers with passengers who go to a bar more than once a month and have a passenger that is not a a kid and had other occupations other than farming, forestry and fishing are more likely to accept the coupon. Majority in this group are in drinking age and most likely live in urban areas because of their occupations. Hence more access to bars where they can actually use their coupons.

4. Customers with the income less than 50K and goes to cheap restaurant are less likely to accept bar coupons. Due to having a low income to begin with, there might be other expenses that customers in this group are spending on other than going to a bar.


Key Findings on the acceptance of Coffee House Coupons:

1. Customers who went to a coffee house less frequently are more likely to use the coffee house coupon, as the 70% acceptance rate shows compared to customers who come to coffee houses more frequently. Just like bar case in bar coupons, less frequent coffee drinkers can use the coupon as an incentive to go to a coffee house.

2. # TO BE CONTINUED..