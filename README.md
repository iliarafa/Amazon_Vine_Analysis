# Amazon_Vine_Analysis

## Overview
The purpose of this analysis is to determine if there is any **bias** toward favorable reviews on mobile electronics from **Amazon Vine** program members. 
Working towards this goal we start by filtering  our initial dataframe to focus on helpful reviews. We determine helpful reviews by dividing helpful review votes to total review votes. If the resulting value is greater than 0.50 the review is included to our new Dataframe. In this new **DataFrame :**<br><br>
## Results

- There are only **4** Vine reviews and **1064** non Vine Reviews<br><br>
![](resources/images/vine_rev.png)<br><br>
![](resources/images/nonvine_rev.png)<br><br>
- **One** Vine review is a five star rating compared to **527** non Vine five star rating reviews.<br><br>
![](resources/images/vine_fivestar.png)<br><br>
- **25%** of Vine reviews were 5 stars compared to **49.5%** of non Vine Reviews.<br><br>
![](resources/images/nonvine_fivestar.png)


# Summary
To confirm positivity bias we would have expected to see a greater percentage of 5 star vine reviews compared to non vine reviews. The results are actually the exact opposite. A greater percentage of non Vine reviews were five star ratings, almost by double. This indicates there is no positivity bias for reviews in the Vine Program. Vine members appear to be more strict, focused and less enthusiastic compared to non Vine reviewers. To further support the usefulness of the program I would then focus my analysis on the quality of the reviews. 

### Quality of Reviews

Diving deeper into it our initial dataset, before we determine useful reviews, we observe a total of 104975 reviews. Breaking this number down we only have 18 Vine reviews in total while there are 104957 non Vine reviews. My first observation is that we are dealing with a very small sample of Vine reviews compared to a huge sample of non Vine Reviews. This raises a question as to if the vine and non vine review datasets are comparable due to their huge difference in size. Setting this question aside for now, we see that 22% of all Vine reviews were declared helpful compared to only 1% of non Vine. We can assume that the Vine Program does boost the review quality without adding positivity bias. 

Initial indication is that the Vine program is working and that it is benefitial for the product,the reviewers and the customers. 

*All questions should be revisited when the Vine program has expanded and the data for Vine reviews is greater.*
