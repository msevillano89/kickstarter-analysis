# Kickstarting with Excel

## Overview of Project

After a successful Kickstarter campaign, Louise was able to fund most of her play ‘Fever’. We will be once again leveraging the Kickstarter dataset to further visualize campaign trends based on their launch dates and funding goals.

### Purpose

Increase Louise’s funding odds by further pinpointing Kickstarter campaign outcome trends based on two variables:

1. Launch Date
2. Funding Goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Due to Louise’s interest in theater-related campaign data, I created a pivot table and pivot chart to visualize funding performance based on when the campaign was launched. The outcome of this analysis is the Line Chart below titled ‘Theater Outcomes Based on Launch Date’.

![Theater Outcomes vs. Launch](https://github.com/msevillano89/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

The line chart shows the number of campaign outcomes (successful, failed, canceled) concerning the month the campaign was launched. This visualization demonstrates that there is a higher likelihood of funding during certain months of the year.

**Note:**
 - Data is filtered to campaigns with the parent category defined as ‘theater’
 - Campaigns that are currently running (live) are out of scope for this analysis.

### Analysis of Outcomes Based on Goals
Another success rate factor that was analyzed is the outcome of the campaigns based on the funding target. For this analysis, I created a table with different goal ranges and calculated the number of campaigns and rates for the different outcomes. Results from this table are illustrated in the below Line Chart titled “Outcomes Based on Goal”.

![Theater Outcomes vs. Launch](https://github.com/msevillano89/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

The line chart indicates the optimal goal ranges in which there is a higher and lower likelihood for a campaign to secure funding

**Note:**
 - Data is filtered to campaigns with subcategories defined as ‘plays’

### Challenges and Difficulties Encountered

No challenges were encountered when developing the report. However, I did find it odd that there were no plays-related campaigns in which funding was canceled, despite some indication that campaigns with a parent category defined as "theater" had some likelihood to be canceled. I manually checked the data set to ensure that the initial findings were correct.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  Looking at the Pivot Table and Line graph created we can draw the following conclusions that will help Louise in her fundraising venture:

  **1. May and June have the highest success rate:** May has the highest successful outcome rate at 67% (111 successful out of a total of 166 campaigns) with June ending second at 65% (100 successful out of a total of 153 campaigns). Moreover, May and June seemed to be the months where most Kickstarter campaigns started. Although operating a campaign during these months does not guarantee a higher success rate, there is an opportunity to dig further and understand why people are more inclined to fund the campaigns.   
 
  **2. Avoid months of January and December:** January has the highest number of canceled Kickstarter campaigns (7 canceled campaigns) while December seems to be the worst performance month with a failure rate of 47% (35 failed out of a total of 75 campaigns. A driver for these results may be due to people’s spending habits during these times, as most likely people are spending their income on Holiday plans, diverting potential fundraising money.

- What can you conclude about the Outcomes based on Goals?

  1. From the Outcomes Based on the Goal line graph we can easily determine optimal ranges where there is a highly likely success – and failure- outcome. For example, goals that are no more than $5,000 and between $35,000 and $44,999 have average successful outcome rates of 70%, with the highest located in the less than $1,000 bracket. On the other hand, campaigns with goals that are equal to or higher than $45,000 have, on average, failure rates of 94%.
   
  2. From the summary table generate, we can also conclude that most campaigns have goals that do not surpass $5,000. As stated above, this seems to be the sweet point where campaigns have the most chance of success.
   
  3. Lastly, we noted that for the subcategory that Louise is interested in starting a campaign (plays), none of the campaigns have been canceled, regardless of the goal target.

- What are some limitations of this dataset?

  There are other drivers, aside from goal target and timing, that could help us understand why some of the fundraising campaigns for the play subcategory were more successful. For example:
  1. **Subject matter:** comedy, drama, classical, etc.
  2. **Marketing:** did this start as a viral video on TikTok? social media marketing? Celebrity endorsement?
  3. **Location:** is the campaign for a play in a small city or a metropolitan area that has a lot of plays that are already available.

- What are some other possible tables and/or graphs that we could create?
  
  1. We could have determined the success rate based on years. Specifically for our Outcomes based on Launch Date analysis, we could have determined any outliers.
  2. Outcomes based on the duration of the campaigns could also provide some guidance on optimal campaign duration
  3. Lastly, a clustered column graph of outcomes by country to determine could help Loise determine if there is an opportunity to expand her fundraising campaign from her original scope.
