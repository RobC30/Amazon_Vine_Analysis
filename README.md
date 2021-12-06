# ____Amazon Vine Analysis____

## __Overview__
The analysis aims to provide insight on Amazon Vine reviews. This will help determine if Vine members positively or negatively impacts a product's five-star ratings.

For this project, we are utilizing Amazon Workspace to create an external environment and using PySpark to perform our analysis. Our dataset is a big dataset of US reviews for Music.

## __Results__

### __Total Number of Reviews__

__Vine Reviews & 5-Star Reviews__

![image](https://raw.githubusercontent.com/RobC30/Amazon_Vine_Analysis/main/Resources/paid.png)


__Non-Vine Reviews & 5-Star Reviews__

![image](https://raw.githubusercontent.com/RobC30/Amazon_Vine_Analysis/main/Resources/unpaid.png)

__Percentages pf Vine & Non-Vine Reviews__

![image](https://raw.githubusercontent.com/RobC30/Amazon_Vine_Analysis/main/Resources/percentages.png)

For the category of Music, less than 1% were Vine reviews and out of that small percentage, none gave a 5-Star rating. Almost all reviews were given by non-Vine members and around 63% of those reviews were 5-Star ratings.

## Summary
According to our analysis, Vine member reviews does not help the category of Music in gaining 5-Star ratings. we can conclude that for the Music category, having Vine member reviews is irrelevant in attaining perfect ratings. 

If we are to investigate this anomaly, we can delve deeper onto the ratings. Instead of only considering 5-star ratings, we can perform a more detailed analysis by creating buckets or bins of 4, 3, 2 and 1-Star ratings.