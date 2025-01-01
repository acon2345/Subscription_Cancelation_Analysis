# Subscription_Cancelation_Analysis

## Executive Summary:
Facing a significant churn issue and major revenue loss, the company leadership wants deeper insights into the reasons behind subscription cancellations to inform future retention efforts. This analysis uses user-reported cancellation reasons to identify trends and provide business recommendations to support future retention.


## Business Problem:
Company leadership has noticed a big churn problem this year which has had a large negative impact to revenue, so they're planning a company-wide retention effort. However, we don't currently have any insights or reporting into why people are churning, so the analytics team has decided to analyze the user-reported data collected in the cancelation workflow within the product to see if there are any trends as to why users are cancelling.
<div class='tableauPlaceholder' id='viz1735765453274' style='position: relative'><noscript><a href='#'><img alt='Subscriptions vs Cancelation Year Over Year ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project2_1&#47;SubscriptionsvsCancelationYearOverYear&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='BDE-Project2_1&#47;SubscriptionsvsCancelationYearOverYear' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;BD&#47;BDE-Project2_1&#47;SubscriptionsvsCancelationYearOverYear&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>

## Methodology:
* EDA
* Product Funnel Analysis
* Data Visualization

## Skills:
* SQL
  * CTEs, CASE, Union, View creation
* Data visualization
  *  Tableau
* Data Wrangling
* Data Cleaning
* Data Science Notebook
* Snowflake Data warehouse

## Results & Business Recommendations

### Results:
* 81.81% of users are selecting at least 1 additional cancelation reason (beyond the first required one), but most users are not selecting all 3 which suggests lack of interest and frustration for the user.
* X% of users reported Y as the primary (first) cancelation reason. The top choices for the primary reason were _______.
* Over time, here's how the cancelation reasons have changed: _____. (Pretend we have enough data to draw these conclusions!)

### Business Recommendations:
* Since most users, have selected Expensive and Not Useful as the reasons to cancel, we should rollout better onboarding and provide more help early on in their subscription to ensure users and understanding the product and finding it useful. If they find the product more useful and valuable, they also many become less cost-sensitive to the value.
* For cost conscious users, we could also launch a rescue tactic at the beginning of the cancelation workflow that offers them a large discount to stay and not cancel their subscription.
* Since the most common cancelation reason for the secondary reason is Went to Competitor, we should research the market and ensure we're keeping up to date with industry trends.

## Next Steps:
* Explore the engagement of canceled subscriptions and see how they interacted with the product. What features did they or did they not use? How often did they use the product? What if we compare them to non-cancelled subscriptions. Does anything stand out that could inform future retention efforts?
* Work with the product manager to understand how we can improve the cancelation workflow by adding in rescue tactics and adding friction without increasing user frustration.
