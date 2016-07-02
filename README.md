# Visualization
http://bl.ocks.org/JasonCabral/raw/c02ad73a33ad1114c3bcdead1ce640fe/

# Summary
In May 2016, there seemed to be a universally accepted notion that the TSA was responsible for many delays in air travel, but the data tells a different story. In fact, airports and airlines are drastically more likely to be the cause of delays, which is shown by the visualization. Contrary to reason, an airline’s revenue has very little to do with it’s ability to limit delays, so check the data before assuming that your costlier ticket will result in a higher likelihood for an on-time flight.


# Design
It was important to me to be able to compare not only the likelihood of each delay type, but also how the top airlines in the country compared to each other and a stacked bar chart allowed for both at the same time.  The color palette was chosen to distinctly separate the delay categories and the tick size and content was chosen to provide as much information as possible without getting in the way. After finding code for an interactive legend and filter buttons, these became essential to my vision as I wanted to tell the reader a story and then give them a sandbox in which to explore. Filtering the data at the outset and then filling in the entire chart when the reader is ready to move on helps tell this data story as do the numerous links to external information. I am particularly happy with the link to the op-ed by the airline industry directly above a chart that completely refutes the claims within. After receiving feedback, tick location was fixed so as to be visible on smaller screens, some of the text was re-worked for clarity, and a sort-by-airline-revenue option was added.


# Feedback

### Reader 1
**What do you notice in the visualization?**
Spirit air lines sucks

It would be cool to have a ratio of airline revenue to delay. I dont know how you would do that, but equate the revenue to something. Seems like just extra numbers when looking at the graph.

### Reader 2
The visualization tells a good story and informative of the various causes of flight delays and proportion of contributors. I think most people would be surprised to see the small proportion of TSA delays compared to the other types of delays. The key of delay types/buttons are a bit small and may be more utilized if they were a bit bigger. Questions I would have would be how does this compare to previous years and current data in 2016?  The main take away I get is that the major causes of flight delays are by far NAS and carrier delays, with security delays only accounting for a small fraction of delays. One of the other take aways is that revenue does not necessarily have an impact on delays.  It might be easier to see if this if I could have sorted the graph by airline revenue high to low.

### Reader 3
Fabulous visualisation. Really clear and to the point. I love the fact that you've linked it to various news stories and used the data to create an alternative story of your own.

**What do you notice in the visualisation?** 
Security delay is not as significant as the articles imply.

**What questions do you have about the data?** 
None

**What relationships do you notice?**
NAS and Carrier delay is the most significant. Weather can be an issue depending on the month. Security delay does vary month by month but not by much.

**What do you think is the main takeaway from this visualisation?**
Security delay is not the main story - the impact of the first graph (Security only) with the main graph (all delay types) drums this in as well.

**Is there something you don’t understand in the graphic?** 
No, clear, well explained, very interesting.

### Reader 4
Jason, it is a cool work here! First thing that I've really loved is the intriguing introduction part which "wets reader's appetite". Overall, storytelling is perfect, just enough to understand data, but not too dry. And external links are on their places. 
One thing was not clear for me - you wrote: "One would also expect that higher fares and baggage fees and similarly, higher revenue for an Airline would lead to better service and and a lower likelihood for delays, but in 2015, this was simply not the case." and I thought first, that y-axis is sorted in the natural order of airline's revenues, which is not true - bars are sorted by the total time of delays. Maybe it would be better to sort by revenue? It would be still pretty easy to compare delay times with this sorting. Or, maybe, it is possible to add a sorting option for reader (?)
 And a minor issue is that when I resize visualization to comfort level of reading, pairs of ticks on y-axis began to overlap. JFYI.


**What do you notice in the visualization?**
It is the explanatory analysis as it should be and having conclusions before the visualization pushes the reader to find the same relations in the visualizations.

**What questions do you have about the data?**
None here, everything is clear.

**What relationships do you notice?**
Same as first question/answer, your conclusions are clearly correspond to what we see in the graph.

**What do you think is the main takeaway from this visualization?**
Maybe, issue with ordering on y-axis here.

**Is there something you don’t understand in the graphic?**
No. You, as author, has definitely done great job for your readers. Thank you! 

# Resources:

http://www.cs.siue.edu/~marmcke/docs/cybergis/mapReduceAirline.html

http://dimplejs.org/examples_viewer.html?id=bars_horizontal_stacked

http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends

https://www.youtube.com/watch?v=6dcj3X6Bfsk

http://bl.ocks.org/phoebebright/raw/3176159/

http://www.rita.dot.gov/bts/press_releases/bts026_16

https://discussions.udacity.com/t/updating-data-in-chart-with-dimple/162873/11

http://stackoverflow.com/questions/15244182/d3-create-buttons-from-an-array-of-string-containing-names

http://stackoverflow.com/questions/3010840/loop-through-array-in-javascript

https://discussions.udacity.com/t/filter-data-with-buttons/172063

http://stackoverflow.com/questions/1208222/how-do-i-implement-a-dictionary-or-hashtable-in-javascript

https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series#shapes

http://stackoverflow.com/questions/20058622/how-to-break-a-line-in-d3-axis-tickformat

http://stackoverflow.com/questions/23291200/dimple-js-how-can-i-change-the-labels-of-a-chart-axis-without-changing-the-data

http://stackoverflow.com/questions/22988109/dimple-js-measure-axis-values

http://dimplejs.org/advanced_examples_viewer.html?id=advanced_responsive_sizing

http://bl.ocks.org/d3noob/7030f35b72de721622b8

http://bl.ocks.org/mbostock/3885705