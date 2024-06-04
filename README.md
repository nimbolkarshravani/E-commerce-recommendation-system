# E-commerce-recommendation-system

Ecommerce recommendation system design using Python on Amazon & Home Depot's dataset
(Please click on the Recommendation System - Paul.ipynb file to see the detailed application of analytics and its interpretation)

A well developed recommendation system will help businesses improve their shopper's experience on website and result in better customer acquisition and retention.

The recommendation system, I have designed below is based on the journey of a new customer from the time he/she lands on the business’s website for the first time to when he/she makes repeat purchases.

The data sets are from

Amazon product ratings by multipe users, Data Source: https://www.kaggle.com/skillsmuggler/amazon-ratings

Home Depot products with descriptions, Data Source: https://www.kaggle.com/c/home-depot-product-search-relevance/data

The recommendation system is designed in 3 parts based on the business context:

When a new customer without any previous purchase history visits the e-commerce website for the first time, he/she is recommended the most popular products sold on the company's website. Once, he/she makes a purchase, the recommendation system updates and recommends other products based on the purchase history and ratings provided by other users on the website. The latter part is done using collaborative filtering techniques.

Strategy/Techniques used:

1) Product popularity based recommendation system targeted at new customers:
Popularity based are a great strategy to target the new customers with the most popular products sold on a business's website and is very useful to cold start a recommendation engine.

2) Model-based collaborative filtering system:
Recommend items to users based on purchase history and similarity of ratings provided by other users who bought items to that of a particular customer.

A model based collaborative filtering technique is closen here as it helps in making predictinfg products for a particular user by identifying patterns based on preferences from multiple user data.

3) Item-item based collaborative filtering system:
For a business without any user-item purchase history, a search engine based recommendation system can be designed for users. The product recommendations can be based on textual clustering analysis given in product description. Predictions done based on other products from the same cluster (based of text analysis of product description) on key search words.

Recommendation system part I: Product pupularity based system targetted at new customers
Product popularity based recommendation system targeted at new customers
Popularity based are a great strategy to target the new customers with the most popular products sold on a business's website and is very useful to cold start a recommendation engine.

Recommendation system part II:
Model-based collaborative filtering system based on customer's purchase history and ratings provided by other users who bought items similar items

Recommendation system part III:
Cold start problem for new businesses: When a business is setting up its e-commerce website for the first time without any historical data on product rating
For a business without any user-item purchase history, a search engine based recommendation system can be designed for users. The product recommendations can be based on textual clustering analysis given in product description.

Top words in the first 3 clusters based on text analysis and clustering techniques applied to product description:
Top terms per cluster:
Cluster 1:
light watt volt led power fan bulb bulbs lighting home

Cluster 2:
painted wood insulation ft primed 65 proposition nbsp residents california

Cluster 3:
water concrete use ft metal used provides designed high fiberglass

Recommendation Technique:
Once a cluster is identified based on the user's search words, the recommendation system can display items from the corresponding product clusters based on the product descriptions.

Summary:
This works best if a business is setting up its e-commerce website for the first time and does not have user-item purchase/rating history to start with initally. This recommendation system will help the users get a good recommendation to start with and once the buyers have a purchased history, the recommendation engine can use the model based collaborative filtering technique.

