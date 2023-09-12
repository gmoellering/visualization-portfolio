# Assignment: Visualizing Government Debt

### Assignment Overview

In this assignment, we are working with a provided dataset and are developing a story to tell with that particular dataset. To accomplish this, I'm going to explore ways to visualize OECD General Government Debt data using a visualization tool called Flourish. 

### Part I

Here is the latest available annual data for 2020 capturing General Government Debt totals as a percentage of GDP including all OAVG countries.

<iframe src="https://data.oecd.org/chart/7bhe" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7bhe" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>

### Part II

The following visualization shows the debt-to-GDP ratios from 1995-2019 using a line chart.

<div class="flourish-embed flourish-chart" data-src="visualisation/14983968"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Part III

**Summary:**
Here, we were asked to create a new visualization using the same data set. One of the primary questions that came to mind as I looked at the line chart above was how countries' debt-to-GDP ratios may have improved or worsened over time. I also wanted to know which countries were the healthiest in terms of their current debt burdens. I found that the sheer amount of data captured in the line graphs had made those things difficult to see, and so I chose to use a type of visualization I hadn't worked with before - a slope chart. I used the slope chart to show how the debt-to-GDP ratios changed over large swaths of time (in this case I used 10 year intervals from 2000-2020). 

What I found interesting when I initially saw the data rendered in this way was that many of the countries with the largest increases in debt-to-GDP ratio from 2000-2020 were ones with already high begining ratios relative to other countries. There were only three countries whose debt-to GDP ratio in 2020 was lower than it was in 2000, and those three already had relatively low debt burdens. To me, this presented an interesting narrative - that most contries largely continued to increase their financial burdens from 2000 onward and that some of the biggest spenders were those most financially at risk in 2000. I fashioned decisions about how to structure the chart, from color scheme to highlighted data, in such a way as to hopefully bring this narrative to the forefront.

<div class="flourish-embed flourish-slope" data-src="visualisation/14984447"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

**Methodology:**
To make this visualization, I used the General Government Debt data from the OECD. I did have to use a subset of this dataset to accomodate the slope chart, which works best when it compares only a few points in time. In order to make the takeaways clear, I restricted the data to decade-long intervals starting in 2000 and running through 2020. The debt-to-GDP values for these years was sufficient to provide the maco-level view I was looking for. I also removed several countries that did not have data recorded for the full 20 year timespan (KOR, MEX, TUR, CHL, ISL, NZL, BRA, ROU, ZAF).

**Closing Thoughts:**
The three visuals produced in this assignment each effectively communicate information but in different ways and at different levels. The first bar chart very clearly shows how countries' debt-to-GDP ratios compare to one another, but it is limited in what it can tell us because it only caputres data from 2020.

The second line chart obviously captured the full scope of the data available. The viewer could find any country and reference its specific chart to see what its debt-to-GDP ratio was for any particular year from 1995-2019. The line charts also effecitvely show ratio trends (improvements and declines) for each country. With additional effort, the viewer can even compare ratios between countries for a given year. What this chart lacks is any sort of narrative or analysis. The individual plot for each country makes it difficult to make side by side comparisons and, specifically, to make those comparisons over time. 

The slope chart improves on the deficiencies of the first chart in that it allows the viewer to easily see how country debt-to-GDP ratios compare over time. It highlight countries of interest to advance a narrative and makes that narrative clear with a title, subtitle, and supporting insights. However, the slope chart does compromise in that it does not provide all the data that the line chart does and does not show comparisons in the final year quite as clearly as the first bar chart. Each chart could be uniquely appropriate depending on the context and the message we wanted to communicate to the audience.

### Back to Homepage

Please click [here](/README.md) to navigate back to my main portfolio page.s