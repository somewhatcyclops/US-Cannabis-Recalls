# US-Cannabis-Recalls
US Cannabis Recalls By State

I have long felt the weight of curating this dataset and yet not sharing it in the hopes that the work would be recognized and formalized by some organization, and it seems that was foolish and idealistic. I'm giving the work away hoping that it can be changed into something useful for consumer safety advocates, regulators, etc. 

This blossomed out of an exercise I did in trying to increase safety awareness around cannabis laboratory issues in 2023 in an article (https://medium.com/cannabis-explorations/when-things-go-wrong-how-do-states-handle-recalls-b08eec9d5e2a?sk=2e7e73fc566edcbf09bc29cbe7521cca), and hilariously though I have an extensive background in data analysis and data engineering - this all bloomed out of one of those quick and dirty analysis that I used to hate in my data warehousing days. That means that it has many known issues. Given the hundreds of hours I've spent curating the data, you'll have to forgive those, and hopefully the next time I sit down to work on this data I'll be fixing some of the major ones. 

I used this data to generate this series of visualizations, [which are now free to use on my Tableau Public.](https://public.tableau.com/app/profile/jamie1773/viz/USCannabisRecallAnalysis/RecallsbyYearStratState#2). 

The known issues are: 
product type needs to be recorded for all 
parse out batches for all states where available, there's something interesting there. 
state by state recall scorecard
Actual Full database back end. 
ability to appropriately tie multiple reasons / full db backend really needed.
Internet archive links for all bulletins, etc.

## Update: 2026-08-10

I've done a pretty large overhaul to Categorizations which should make little difference to grouping but a larger difference to me when I go to overhaul how the entire thing works with reasons and products and the many to one relationships they need to introduce. (I'm at the point where I can't just force Cartesians and filter them out.)

I added a Dashboard. [Dashboards are cool.](https://public.tableau.com/app/profile/jamie1773/viz/20260807USCannabisRecalls/YearDashboard#2)
