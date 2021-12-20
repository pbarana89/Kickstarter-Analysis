# Kickstarting-with-Excel-Challenge - Peyton Arana

## Overview
The overview of this project was to help Louise determine how projects had fared in relation to their launches and their funding. We were able to use the data that we already gathered from Kickstarter to create visualizations and analysis that showed this information. Louise's initial need of $12,000 for her play put her in a goal category where 54% of plays successfully found their goal. 

## Analysis
The analysis was created by gathering the information from Kickstarter. Then the data was filtered so that I could focus on Louise's category which was theater and further filtered down to the subcategory of plays. Louise also wanted further information about other similar plays that had success in the UK, so I used the Vlookup function to find 5 similar plays to show information on their goals and outcomes.  

### Analysis of Outcomes Based on Launch Date
In [“Theater Outcomes vs Launch”](https://github.com/pbarana89/Kickstarting-with-Excel-Challenge/blob/1b95e8786a2bca33c0ddb6de8830ef51df2dd40c/Theater_Outcomes_vs_Launch.PNG) I used pivot charts to show how plays did based on their launch dates. The image showed the highest success rate by plays that launch in the summer. While this is the case, it does seem Kickstarter strongly supports plays as there was no month where plays failed at a greater rate than succeeded. This would suggest that as for places to search for funding Kickstarter is a valuable place to go for people looking to do smaller budget plays.

### Analysis of Outcomes Based on Goals
Which that point is shown in the "Outcomes Based on Goal" image, as I was able to show based on the goal amount the percentage of plays that succeeded and failed. I was able to use this via countifs and sum functions. The plays under 15k or less had a higher chance to succeed, and they also allowed for a little more reliable data. As the amounts grew the total amount of plays diminished, so any kind of reliable information started to diminish. There may still be value in the information that these plays give us, but the variance created needs to be noted.

### Challenges
I did encounter problems when gathering this information. When I used the countifs functions I did not get the same information as the example and so I had to figure out if the example chart was using other data, or if I was pulling incorrectly. I first checked the functions and those were correct, then I tested the data and looked for a 40k play that was successful. I found 2 and this matched with the example chart, then I looked at my functions again and I had incorrectly entered the values that I was searching. An example of this was I had written less than 39999 and then in the next section greater than 40000, this left out some situations where the number was exact. Once this was fixed, I pulled the correct numbers and my chart matched the example.      

## Results
The dataset as I stated has a wealth of information that we can view. This large amount of data still has its limits. The bigger budgeted plays were very rarely put on Kickstarter, so it hard to know if someone was to put a 100k play on Kickstarter if it would be successful based on what we can already see. This could be due to bigger plays using more traditional funding methods or the limited history of Kickstarter. The dataset also limits what we know about donations. We can see how much is being donated on average, but are these donations coming from the country where the play is located? If we could see if donations were coming on a local level, then it might forecast how much interest will be created when the shows start to sell tickets.

A box plot would be very valuable to further gather information on the data. The ability to see in detail the median, the quartiles, might give further details that our current information does not convey. We could also use a scatter plot to show successful plays based on totals and it might allow for more information to be attained from the data instead of using a line chart.


