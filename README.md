# YELP-3NF
Data engineering &amp; Cloud  Using Amazon Web Services - Performed  (ETL - Extract , Transform , Load ) With multiple data sets. 

What is Yelp?

Yelp is a popular online directory of local businesses from various industries: bars, restaurants, spas, gas stations etc. Results of a search query are filtered by geographical location, business type, price ranges, and unique features. The idea behind Yelp is for users to leave their rating and a review of their experience with an establishment. It can be a treasure chest of guidelines on how customers view your business, and what improvements can be made to see more happy customers. So, how exactly can Yelp reviews help us explore the satisfaction of our customers?

Our project idea - Goal :

We use to create data pipeline that converts the non-relational Yelp dataset, which is dispersed over JSON files in an Amazon S3 bucket, into a 3NF-normalized dataset kept on Amazon Redshift. The resulting schema serves as the authoritative source for analytical queries and business intelligence (BI) tools, guaranteeing data consistency and referential integrity across tables. The data was further enhanced with demographic and weather information from outside data sources.

Throughout the procedure, we use ETL tools such as :

#1 Apache Spark,

#2 Amazon Redshift, and

#3 Apache Airflow .

in progress we also used Amazon Athena , AWS Crawler and Glue as well etc...
