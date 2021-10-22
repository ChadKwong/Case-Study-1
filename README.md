# Introduction

Brittany Lewandowski and Chad Kwong were provided with the Beers and Breweries data sets from the CEO of Budweiser, Professor Lindsey, and the CFO of Budweiser. Brittany and Chad were asked to analyze these data sets and provide answers to the following seven analysis questions: 

1.	How many breweries are present in each state?

2.	Address the missing values in each column.

3.	Compute the median alcohol content and international bitterness unit for each state. Plot a bar chart to compare.

4.	Which state has the maximum alcoholic (ABV) beer? Which state has the most bitter (IBU) beer?

5.	Comment on the summary statistics and distribution of the ABV variable.

6.	Is there an apparent relationship between the bitterness of the beer and its alcoholic content? Draw a scatter plot.  Make your best judgment of a relationship and EXPLAIN your answer.

7.	Budweiser would also like to investigate the difference with respect to IBU and ABV between IPAs (India Pale Ales) and other types of Ale (any beer with “Ale” in its name other than IPA).  You decide to use KNN classification to investigate this relationship.  Provide statistical evidence one way or the other. 

Using RStudio, Brittany and Chad completed this analysis. Answers to the above analysis questions, along with the R code Brittany and Chad ran can be found in this project deliverable. The PowerPoint presentation given to Professor Lindsey and the CFO of Budweiser is included as well. Comments explaining each piece of code, as well as answers to each of the analysis questions are present in the RMD file. Should you have any additional questions, please contact Brittany or Chad at: blewandowski@smu.edu and ckwong@smu.edu. 

Note about RMD File: There were issues with knitting some of the code that was verified to work. As a result, for the RMD file to knit, some code was commented, but all code available will function. There should be no issues as both partners have code for each question. All available questions are answered and RMD file will display all appropriate answers and plots.


# Recommendations

After analyzing the Beers and Breweries data sets, Brittany and Chad have 3 recommendations they feel confident will help Budweiser increase their revenue and better satisfy their customers:

1.	Produce and distribute beer with higher ABVs and IBUs.
2.	Sell beer in the states of Colorado, California, and Oregon.
3.	Leverage Naïve Bayes Classification for inventory management.

# Conclusion

Upon analyzing both the Beers and Breweries data sets, Brittany and Chad determined:
•	Budweiser has the most breweries in the states of Colorado, California and Michigan and the least breweries in DC, South Dakota, and West Virginia.
•	Budweiser has a higher mean ABV and IBU at its breweries than the industry averages (5.9% ABV, 42.73 IBU).
•	Kentucky is the state with the highest ABV beer.
•	Oregon is the state with the most bitter beer. 
•	The distribution of the ABV variable indicates that customers prefer beers with higher ABVs.
•	There is evidence of a positive correlation between ABV and IBU. Due to confounding variables, we cannot suggest that the relationship is linear without further analysis. 
•	KNN classified beers as Ales or IPAs based off of their ABVs and IBUs with an accuracy of 84%.
•	Naïve Bayes classified beers as Ales or IPAs with a 92% accuracy. 


 
