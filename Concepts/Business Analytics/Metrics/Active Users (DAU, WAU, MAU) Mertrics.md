## The best definition I've found
Source: [chartio.com](https://chartio.com/learn/product-analytics/what-are-active-users/)

The **active users** metric counts the number of unique users who engage with a web site or application within a particular period of time. Active user counts are a high level [product metric](https://chartio.com/learn/product-analytics/top-product-metrics/) to measure growth, [churn](https://chartio.com/blog/the-only-three-churn-calculations-you-need-to-know/), and product stickiness.

The criteria used to define a user as active will depend on the company and the product. For a website or application, activity could be defined as simply opening the site or app, require taking a specific action, or involves performing a certain number of actions. All users who perform the activity criteria are counted over a set amount of time.

The steps to compute active users can be deceptively simple, but can become complicated depending on how activity is defined.

## Useful decompositions
* DAU = DAU of new users + DAU of returning users
* DAU = Conversion * DBU
* DAU of new users = DAU of new organic users + DAU of new users from the marketing campaigns
* DAU of returning users = DAU of returning users by retargeting marketing campaigns + DAU of organically returned users
* DAU  = 0.01 * MAU * Stickness. See [What is an active user?](https://www.adjust.com/glossary/active-user#what-are-the-most-commonly-used-measurement-periods-for-an-active-user)

## Mathematical properties
* Non-cumulative, so WAU can't be computed on top of DAU.
* In some cases DAU = sum(DAU per group), but only when every user is attributed to one group. If users can change groups during the measured period, you'll double-count them.

## Caveats
TBD

## Usefulness for eCommerce business
TBD