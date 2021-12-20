# Analyis of Kickstarter Campaigns
Louise needed help analyzing some data for a play she wanted to fund through Kickstater. After we helped her with analyzing the data to determine the trends between number of backers, the relationship between goals and pledged difference, etc., she wanted to know if there was a relationship in different campaigns in relation to their launch dates and their funding goals.

## Analysis and Challanges 

### Determining Outcomes Based on Launch Date 

![Theather_Outcomes_vs_Launch](https://user-images.githubusercontent.com/41711693/146713071-ce06baed-b4e9-4d50-bd55-f5312b6ef4e1.png)

A Pivot Table and a Chart was created to see the outcomes based on when the theater company Kickstarter was launched. First, we made a Year column and used the YEAR() function on Excel to extract only the years from the Date Conversion Column. That was going to be useful to us once we create the table. I took the infomation from the Kickstarter sheet on the Kickstarter Challange workbook, and inserted a Pivot Table. The data I used to make this table was Years and Parent Category on filters, Outcomes on columns, Date Created Conversion on rows, and Count of Outcomes on the values.  Then it was sorted in it ascending order to show the succesful first. Then a chart was created to have a better look at how the data looks overall. I think that looking at the results with a chart is much easier than just analyzing the numbers in the table alone. The patterns can be viwewed much clearer. 

I felt very comfortable with this chart, but I think that something that might have been challenging would have been determining the correct way to set up the table if there were not too many instructions on what needed to go where. I think I would have eventually gotten to it, but it would hava taken a much longer time. 

### Outcomes Based on Goals Chart

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/41711693/146713355-35741ffc-bcb6-4b70-80f7-4074f4a73919.png)

In this part I got to use the COUNTIFS() function to count the entire number of successful, failed, and cancelled plays depending on the goal. The goals we looked at were $1,000 to $50,000. Once we got these total numbers it was time to calculate the percentage of each outcome based on the total number of projects. I also created another chart to have an overview of the data to analyze. I did this through inserting a line graph and then filtering out the rows I did not need. 

The challange I encountered through this part was on making the chart. I was originally trying to make it with a Pivot Table, but it was not working out. I later tried to do it by inserting a chart from the table we created but could not figure out how to only use the percentage colums and the rows. I eventually looked it up on Google and found a way to do this. I did it by right clicking and selecting "Select Data." That took me to the chart that I needed.

## Results

The Theater Outcomes by Date shows that the best month to launch a Theater Kickstarter is April. This month saw an approximate 21% increase. If you look at the table you can see how steep the line for successul campaigns is from April to May. Also, that July-October are not the ideal months to start a campaign. As you can see from the chart, the line takes a pretty deep dive at this time only to increase a small amount the then plummet once again. 

The Outcome Based Goals show that campaigns asking for smaller amounts of money are the most successful. As soon as the goals got to over $5,000 then the percentage of success dropped. It is interesting to see that after $5,000, the most successful goals were $35,000 to $34,000 and $40,000 to $49,999. 

A limitation that I see from this data set is that it might be too broad. If you only look at the plays, then it is not going to tell you which plays perform better. I think this can be important because it can really change the course of the campaign. Perhaps musicals do better than tragedy depending on the month or season. Genres can definitely have an impact on the outcome of the campaign, backers can have more faith in one than the other. 
