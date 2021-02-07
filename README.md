# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project is to determine the likelihood of a kickstarter project succeeding by looking through obtained data on previous projects from all manner of categories, then comparing their success through a number of filters including their category or subcategory, their original goal amount, and which month they were introduced. By filtering the data in these various ways, we can produce graphs detailing how success rate varies between the different criteria we apply to the data we've already accumulated.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The actual date of launch for any Kickstarter campaign could prove to be rather important. A date could signify how much money potential backers could have in order to fund a campaign, and in times that align with low backer fund levels. As such, it's important to know when best to start the campaign to maximize its likelihood of success.

In order to determine which timeframe would be best to start a new campaign, we took a look at each month and looked at the rate of success, failure, and cancellation of every Kickstarter campaign that fits within the Theater category for each month. After the Theater category campaigns were tabulated and separated, the results were tabulated and arranged into a line graph detailing the numbers of each result by month.

![A graph of Outcomes by Launch Date](https://github.com/SirNancyTheNegative/kickstarter-analysis/tree/main/resources/Theater_Outcome_vs_Launch)

Overall, May appears to be the best month to start a theatre kickstarter campaign. Of the 166 Kickstarter campaigns introduced in May, 111 of them succeeded, compared to the 52 failed campaigns in the same month. Inversely, December is by far the worst month to attempt to start a theater campaign, as of the 75 campaigns that had finished, a mere 37 of them succeeded, with the remainder of them having failed or been canceled. To be more general, the most successful times to start a campaign for a theater-oriented Kickstarter campaign would be anywhere between April and July, while September through January is a stretch of time where the chance of success is at its lowest.

### Analysis of Outcomes Based on Goals

Launch Date is not the only factor that needs to be considered when planning a Kickstarter campaign. It could be guessed as such, but the amount you aim to gain from potential backers will often determine whether or not the campaign will actually backed, with some people being put off by a large backing goal for a comparatively small project. On the other hand, by having a small goal for a comparatively huge and harrowing project, you might not actually get enough money to see your project through to the end.

In order to determine the success of varying goal levels, we first have to determine how best to group them. For the sake of simplicity, the goals are separated into groups with a range of $5,000 (e.g. Under $5,000; $5,000 - $9,999; etc.). From this, we singled out every campaign with the Theater category and "plays" subcategory, and separated them into these groups. We further evaluated them by their successfulness (i.e. success, failure and canceled), and formed partitions based on their success. We then determined the percentage composition of each group by its partitions, and put them into a line graph comparing those percentages as the perceived value of the campaign increases.

![A graph of Outcomes by Funding Goal](https://github.com/SirNancyTheNegative/kickstarter-analysis/tree/main/resources/Outcomes_Based_on_Goal.png)

What we get from this process is a graph with a few notable points about it. The first and most obvious one being that of all the campaigns we examined, none of them held a status of "canceled", and as such the percentage cancelled remained at 0% for every range we observed. The second is that as we move along the ranges, the two lines denoting "successful" and "failed" start to move erratically, without a clear trend to them. This can be seen in the graph around the range of $25,000 to $29,999. Before and at this point, we can see a consistently downward trend in percentage successful, and a consistently upward trend with percentage failed, suggesting a negative correlation with the percentage of successful campaigns with increased campaign funding goals. However, beyond that, the data is inconsistent and chaotic, suggesting no real correlation.

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From the data we collected from our analysis of outomes based on launch goals, it is fair to say the success of a Kickstarter campaign is negatively influenced by its proximity to Christmas. By our data, the months of September through January are a period where campaigns in the Theater category are the least successful, and around the month of December the number of successful campaigns diminishes the most with respect to the total number of campaigns for that month. This result is slightly unsurprising -- Around the holidays, money often becomes the tightest in households that celebrate, as the social obligation of gift-giving produces strain on finances and, as a result, potential backers might not have as much funding to spare, which leads to fewer successful Kickstarter campaigns.

A second conclusion about the outcomes we can make is that May is by far the most successful month for Kickstarter campaigns, and that it's also the most popular month for other campaigns to be started. Between April and May, the number of successful campaigns increases drastically, far more so than the number of failed campaigns, and when May turns to June, the number of successful campaigns decreases faster than the number of failed campaigns, as can be seen in the graph. This points to May being a local maximum in terms of the success rate of Kickstarter campaigns, and as such, it would be an ideal time to introduce a new campaign in terms of maximizing its chances of success.

- What can you conclude about the Outcomes based on Goals?

The amount of data we have for the Outcomes based on Goals is insufficient to produce a complete picture. While everything below $25,000 produces a graph that suggests a negative correlation between the percentage of successful campaigns and increased funding goals, the data beyond that is insufficient to produce an accurate picture. For example, because we only have one event in the range of $45,000 to $49,999, we would either get a 100% success rate or 0% success rate, which is, suffice it to say, unhelpful when it comes to planning within that range. The other data points above $25,000 similarly do not produce much of a data set to work with. So, until such a time as more data points become available, we cannot come to a satisfactory conclusion that would help determine the success of different funding goals.

- What are some limitations of this dataset?

The dataset we're tasked with working with has a number of limitations to it. The first, that we've explained in the conclusion on Outcomes based on Goals, is that in terms of working with higher funding goals, we don't have nearly enough data points to reach an acceptable conclusion. Another notable limitation that hasn't been mentioned yet is the subjectivity of the pitch of each Kickstarter campaign. Having an interesting campaign often isn't enough -- a campaign creator needs to be able to come up with ways to sell their idea to the masses -- be it with perks that would be given to backers at the end of a successful campaign, or with trying to make it sound better than it might be otherwise. Oftentimes these perks and selling points would make up the difference between a successful campaign and a failed one, and the margin in which they help the campaign is not easily measurable.

- What are some other possible tables and/or graphs that we could create?

From here, there is still much we can do with this dataset that we haven't done. For one, we don't yet know the extent of the goals with respect to each month, so producing a graph that divies the campaigns that started each month into their different goal ranges would help show how the Outcomes based on Launch Date and the Outcomes based on Goals correlate with each other. In doing so, we could find a different, more concise answer as to what month would work the best for different funding levels, which would help build a more developed plan of action in deciding how best to go about creating a Kickstarter campaign.

Additionally, we could develop a table that looks exclusively at failed campaigns, so we can determine just how far off those campaigns were from success, and use that data to help build a plan for failure in such a scenario. However, I believe that the former would prove to be more beneficial than the latter, as there exists a fine line between preparing for the worst and outright pessimism.