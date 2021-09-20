# Sales Conversion Optimization Project

**Content:**

The data used in this project is from an anonymous organisation’s social media ad campaign.

1.) **ad_id**: an unique ID for each ad.

2.) **xyzcampaignid**: an ID associated with each ad campaign of XYZ company.

3.) **fbcampaignid**: an ID associated with how Facebook tracks each campaign.

4.) **age**: age of the person to whom the ad is shown.

5.) **gender**: gender of the person to whim the add is shown

6.) **interest**: a code specifying the category to which the person’s interest belongs (interests are as mentioned in the person’s Facebook public profile).

7.) **Impressions**: the number of times the ad was shown.

8.) **Clicks**: number of clicks on for that ad.

9.) **Spent**: Amount paid by company xyz to Facebook, to show that ad.

10.) **Total conversion**: Total number of people who enquired about the product after seeing the ad.

11.) **Approved conversion**: Total number of people who bought the product after seeing the ad.


**Goal:** 

Optimizing conversion rate and predicting future sales

## Insights

**Correlations:**
* Approved Conversion is more correlated with number of impressions than Clicks and Money spent on ad, and highly correlated with Total Conversion

* Total conversion is also highly correlated with number of impressions

**Campaigns:**
* Campaign C has most number of ads and best approved conversion rate

**Age group:**
* In campaign_c and campaign_b, the age group of 30-34 shows more interest, whereas in campaign_a the age group of 40-44 shows more interest.

**Gender:**
* More money was spent on women with less approved conversion

**Money spent:**
* There is a moderate positive correlation between money spend on AD and approved conversion

**Product bought after clicking the ad:**
* It looks like women tend to click more than men, but men buy more products after clicking the add.

* People who are 30-34 years old has more tendency to buy the product after clicking the add.

**Product bought after enquiring the ad:**
* It looks like men buy more products than women after enquiring the product. However women tend to enquire more about the product.

* It seems people in age group 30-34 are more likely to buy the product after enquiring the product.

## Marketing Campaign Improvement

**Which marketing campaign should we focus on?**

As most purchases came from Campaign C (with less money spend), we should focus on that campaign:
    
* Campaign C possesses the best results and profits, despite the cost.

* However, Campaign A should also be given a little more attention. Although approved conversion rate was lower, customer acquisition cost (CAC) also was.

**Which demografic group should we focus on?**

* We should focus on 30-34 years old men, since approved conversion rate is higher and less money was spent on them.

* Less money should be spent on 40-44 and 45-49 age groups and women (all ages), since the approved conversion rate is lower.

* People with interest types up to 35 and after 100 should be given more attention, since there are potential buyers there.

**Which creative strategy could we use in the future?**

* We should increase the number of ad exposure (impressions) since it's highly correlated with total conversion rate. 

* Therefore, it would be a good idea to use inexpensive ads with high exposure to get potential customers to enquire about the product. Other marketing strategies could be used to get them to buy the product. I.e: pricing strategy, brand image, market positioning, quality.

## Models

-Linear Regression

-Random Forest Regressor
