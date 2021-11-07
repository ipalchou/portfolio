The data visualization I have chosen is from the WHO website on covid cases. I have specifically chosen the visualization under 'Situation by WHO Region' .
![image](https://user-images.githubusercontent.com/92895925/140662813-c1631520-8eb6-427c-84e3-af60e140e464.png)

The data extract to create the second graph was taken from https://app.powerbi.com/view?r=eyJrIjoiYWRiZWVkNWUtNmM0Ni00MDAwLTljYWMtN2EwNTM3YjQzYmRmIiwidCI6ImY2MTBjMGI3LWJkMjQtNGIzOS04MTBiLTNkYzI4MGFmYjU5MCIsImMiOjh9. This site gave me the excel file to recreate the graph.

While it is true that the visualization is not extremely poor, I thought that this visualization can be made better .The Graph at the left is solving 2 purpose. One working as a legend for the graph to the right. It is also narrating its own story. The graph to the left is conveying story about the total confirmed covid cases for All time across WHO regions. The graph to the right is telling us about the daily covid cases from Jan to Oct. I think the stacked area chart can be a bit uncomfortable to visualize. After doing some analysis, it was seen that in May 2021, South east asia had the highest number of covid cases. But the stacked area chart can make it confusing to determine such information. 

I had feedback from 2 people AJ- A MISM cohort. SC - A working professional

For the Left chart, my wireframe (created using Balsamiq) looked something like below:
![image](https://user-images.githubusercontent.com/92895925/140663002-3990dc4a-65b7-451c-b2a1-6783a41ef3f3.png)

Feedback:
- Can you tell me what you think this is?
 AJ-number of covid cases in 6 regions arranged in descending order.
 SC-number of covid cases in 6 regions arranged in descending order.

- Can you describe to me what this is telling you?
AJ-number of covid cases in America is the highest and Africa is the least.
SC-number of covid cases in America is the highest and Africa is the least.

- Is there anything you find surprising or confusing?
AJ-No
SC-No
- Who do you think is the intended audience for this?
AJ-Anyone who wants to know which region has the highest number of covid cases
SC-everyone

- Is there anything you would change or do differently?
AJ-Add a time frame maybe
SC-Not sure why americas,europe and south east asia have same colors

For the second chart , my wireframe (hand-drawn) looked something like below: 
![image](https://user-images.githubusercontent.com/92895925/140663037-7d212f88-170e-4117-a3c4-d5fb9740943a.png)

- Can you tell me what you think this is?
AJ-The graph describes how the number of covid cases differed between May and November in 6 regions.
sc- Covid cases trend for 6 months

- Can you describe to me what this is telling you?
AJ-Covid cases started off in America and have been increasing when compared to other regions. Not clear on the exact numbers.
SC-America has the highest cases and Africa lowest

- Is there anything you find surprising or confusing?
AJ-There is no data on the y-axis
SC-I dont see the exact figures 

- Who do you think is the intended audience for this?
AJ-No one. Needs to be more specific for anyone to use
SC-Can be everyone

- Is there anything you would change or do differently?
AJ-Would be more specific by adding dates and the number of covid cases for that date. Would also prefer not to draw by hand.
SC-I want to see the exact numbers of daily covid cases.

After going through the feedback , I realized the importance of an appropriate title and values to be shown. I had to drop the idea of creating decreasing boxes for total confirmed covid cases as Flourish or Tableau didnt have the capability and hence I re-created a donut chart with exact figures shown on it and a title which makes sense.I made sure that distinct colors are used so that we clearly differentiate between countries.

<div class="flourish-embed flourish-chart" data-src="visualisation/7757515"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

For the chart which gives the daily covid case count, I have added a title which makes proper sense. I have created a multi line chart in flourish. Upon hovering on the points, the exact figure of daily covid cases can be seen. The line chart makes the visualization much neat. Because we can easily see which point is the highest , it is easy to make out the region with highest covid cases at any point in time. This can be difficult with the stacked area chart as was in the original data visualization.
<div class="flourish-embed flourish-chart" data-src="visualisation/7758120"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
