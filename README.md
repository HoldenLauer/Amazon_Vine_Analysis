# Amazon_Vine_Analysis
## Overview of the analysis
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members. Using PySpark to extract the dataset and transform the data. Then, connect to an AWS RDS instance and create a database connection into pgAdmin. For this project I chose US reviews for video games.
## Results
### Total Number of Reviews
- Vine Reviews

![total paid reviews](https://user-images.githubusercontent.com/110861876/204440476-cc76e43d-f523-4784-aaf7-23d7a72afc47.png)
- Non-Vine Reviews

![total unpaid reviews](https://user-images.githubusercontent.com/110861876/204440503-81a6381e-022a-4d9e-b96f-0503e3461d7e.png)
### Total number of 5-star reviews
- Vine Reviews

![paid5star_reviews](https://user-images.githubusercontent.com/110861876/204440599-bcbf1fff-4fe3-4f35-8eb6-baaf09122981.png)
- Non-Vine Reviews

![unpaid 5 star reviews](https://user-images.githubusercontent.com/110861876/204440636-829b802e-7ad4-4f81-9c60-819c41da679a.png)
### Percentage of 5-star reviews
- Vine Reviews

![paid 5 star percent](https://user-images.githubusercontent.com/110861876/204440695-3b8f29cf-3039-44e1-b8db-ac0ee041b7e5.png)
- Non-Vine Reviews

![unpaid 5 star percent](https://user-images.githubusercontent.com/110861876/204440729-0411e0b5-6731-412d-9084-609f7c8b2008.png)
## Summary
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
An additonal analysis is that we could run a .summary on the paid and unpaid Vine reviews to get a statistical distribution of the star ratings.
