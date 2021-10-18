# Amazon_Vine_Analysis
Amazon Vine Analysis with PySpark and AWS

## Overview of Project

To use one of the 50 datasets of Amazon products and determine being a Amazon Vine members increases the bias of the members in a specific direction. In order to achieve this purpose Pyspark will be used to perform the ETL process of loading the Amazon dataset from which the analysis will be performed. 

## Results

![Vine_Paid](https://github.com/DavidFGitH/Amazon_Vine_Analysis/blob/main/Resources/Vine_Paid.png)

![Vine_NotPaid](https://github.com/DavidFGitH/Amazon_Vine_Analysis/blob/main/Resources/Vine_NotPaid.png)

For this project, we chose the video games dataset, from which there were a total of 94 Vine reviews and 40471 Non-Vine reviews. Of those reviews, 48 of the Vine reviews were 5 stars and 15633 of the Non-Vine reviews were 5 stars. This gives us about 51 percent of Vine reviews being 5 star and 38.7 percent of Non-Vine reviews being 5 star.

## Summary

At least from a surface level analysis, we can find that there does seems to be some positivity bias for Vine member reviews, as 51 percent of Vine reviews are 5 star, about 11 percent more than the 38.7 percent of 5 start Non-Vine reviews. However, more work would have to be done to determine whether this is statistically significant, especially since the number of Non-Vine reviews vastly outnumbers the number of Vine reviews, over 40000 to 94 respectively. This means one analysis that could help determine the prevalance of positivity bias would be to find more advance statistics such as standard deviation of rating scores for Vine and Non-Vine reviews to do something like a t-test in order to determine whether there is a statistically signficant difference between Vine and Non-Vine reviews. Another analysis that could be done would be to add an additional element for control such as specific products with a good number of Vine and Non-Vine reviews which would be important in determining on a per product basis whether being a Vine member introduces positivity bias.
