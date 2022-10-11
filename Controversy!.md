# Visualization Blog I: Oct. 10, 2022
## Controversy!
### Immigration Visualizations
This week's visualization blog focuses on controversy! My topic of choice is immigration, which is growing increasingly more controversial as governments worldwide 
shift further right on the political spectrum. The way in which you present immigration information in a visualization can have major impacts on the way audiences
interpret that information, shaping their opinions and understandings of this crucial policy area. Not only can you instill messaging into visualizations, but you can
inhibit meaningful analysis of data by simply providing too much or too little information in a visualization. 
<br />
<br />

The following immigration visualization is one that I find many issues with:
<br />
![image](https://user-images.githubusercontent.com/91711083/194986955-c4f3f5a1-0f9f-4b98-a772-66d47c02c813.png)
<br />
This is a picture of a plot showing where people migrated to and form, and how many people migrated between regions between 2005 and 2010. If you are interested
in learning more about this graph and its creators, visit [this website](http://download.gsb.bund.de/BIB/global_flow/). Looking at the non-interactive still of
the visualization, it is very difficult to see what is going on. For me, it took a while to discern which strings represented emigration out of a region versus
strings that represented immigraton
into a region. While the interactive version of the graph does clear this up, the still graph makes it difficult to understand other key information
such as the number of people moving to and from. It is not an easy task to determine the area of each string relative to the rest, so you cannot
immediately or reliably compare the immigration figures by just looking at the picture. Perhaps a table would have been more suited to display the ample data. 

<br />
Here is an example of an immigration visualization that I like, created by the McKinsey Global Institute:
<br />
<img width="186" alt="image" src="https://user-images.githubusercontent.com/91711083/194994481-814853cc-b655-4bcb-8eb7-c4712f67e33d.png">
<br />

To me, this graph is successful because it plainly and clearly showcases statistics on age and sex for the refugees and asylees of the world. The labels are easy to 
understand, their placement is perfect, and they aid in the interpretation of the pie graph, which can be difficult for some audiences to analyze without
knowing the percetange makeup of each pie graph portion.  <br />

I am not sure as to how I would exactly replicate this visualization in R, but to create something similar, I would use the following code:

#library(ggplot2) <br />

#ggplot(df, aes(x = "", y = perc, fill = answer)) +
  geom_col() +
  geom_label(aes(label = labels),
             position = position_stack(vjust = 0.5),
             show.legend = FALSE) +
  coord_polar(theta = "y") + labs(title = "title", subtitle = "subtitle")
  <br />  <br />

Finally, this is an immigration visulization I created:<br />
![image](https://user-images.githubusercontent.com/91711083/195007168-5a352b44-c395-40e0-88c6-c1049464b6ed.png) <br />
Using data from a 2019 study done by NORC at the University of Chicago, I created a bar plot that shows the opinions of polled Americans regarding the number of legal
immigrants of America, with corresponding information on political party for each particular opinion. The count of the number of people polled is also shown. 
I tried to make an interesting comparison between political party and immigration opinion, while also making a clear and concise graph that represented
the number of people polled in comparison to parties and immigration opinions. 
