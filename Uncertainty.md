# Visualization Blog II: Oct. 31, 2022
## Uncertainty!
### Food Spending Visualizations

<br />

This week's visualization blog includes improving upon visualizations and adding elements of uncertainty. I was inspired by the particularly bad visualization 
pictured below:

![image](https://user-images.githubusercontent.com/91711083/199404675-4fa0c22a-4d6d-41cb-9159-150792cbcc0b.png)

<br />

That image comes from a blog site and content hub for all things kitchen related, The Kitchn. I do appreciate the original idea and intentions behind the visualization:
to interestingly showcase weekly food spending for average Americans. And, while the graph is visually pleasing, it is incredibly hard to discern the area sizes
of each respective spending category. The category with 22% of the respondents looks larger than the category with 26% because of the 2D format and due to 
the fact that each square of data is encased in the next one irregularly.
I also wish there were more information included on income groups, plus adding a measure of uncertainty would also 
improve the visualization. 

<br />

With all of these criticisms, I used data from the U.S. Bureau of Labor Statistics to create this improved graph:

<br />


![image](https://user-images.githubusercontent.com/91711083/199419945-df278cf9-7862-4c20-a713-e10b0fa98dcb.png)

<br />
I think this is an improved version of the original visualization in many ways, although these two graphs fundamentally show different information. The first graph
shows percentages of consumers by their weekly food spending, whereas my visualization shows average weekly food spending for different income groups along with 
the 95& confidence intervals for the data. I thought it would be more interesting to show income groups, because you get a better idea of *who* is making up the 
food spending categories showcased in the original graph.

<br />

I wasn't sure how to include this in my graph, but it would have made an even better visualization if I included what the income quintiles actually meant in dollar terms. 
For reference, each respective quintile (in ascending order) has an average gross income of 
$13,165; $34,767; $61,214; $100,527; and $226,386. 

<br />


So, while weekly food spending wasn't proportional to gross income (ratios of the income groups
are not equal to the ratios of the weekly food spending figures), there is certainly a correlation between
gross income and food spending, which my graph conveys. The confidence intervals show that 95% of the real population is accounted for in the figures included
in the sample data, so with no overlap between confidence intervals of the various income groups, we can be very confident in the fact that in the actual 
American population, there is the correlation
that we have observed in the sample means. 
