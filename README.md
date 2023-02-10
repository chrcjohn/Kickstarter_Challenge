# Kickstarter_Challenge
## Project Outline
# The purpose
The purpose of this project is to analyze a dataset and retrieve results based on fundraising start dates and target amounts. This makes it easy for Louise to understand when is the best time to start fundraising and what the specific amount to aim for is. Make your fundraiser successful.

A Kickstarter campaign is a great way to fund art her projects without overburdening creators. Kickstarter campaigns allow creators to focus on creating content while fundraising for their projects. The project offers a glimpse of several Kickstarter campaigns designed to raise funds for various plays. Some campaigns were successful, while others fell short of their goals. The data provided helps identify trends that may have contributed to the success or failure of the campaign.

The hard part was the results based on the goals. I had to create a separate formula for each row of successes, failures, and abandons, which required a lot of concentration. Also, the Kickstarter sheet had the tricky part of converting Unix timestamps to actual dates.


## Result
Two conclusions can be drawn about the theater results by start date:
![Theater Outcomes by Launch Date](https://user-images.githubusercontent.com/23088053/217991478-56dbb6a1-6011-48d7-9ab4-50c623a059b5.png)
![Outcomes Based on Goals](https://user-images.githubusercontent.com/23088053/217991495-f87cc7e3-1185-4288-8302-060a8c0b2949.png)


The month he launched his most successful Kickstarter campaign was May.
Campaigns launched in June, July, and October had similar numbers of failures.

## Conclusions are drawn from goal-based results.

Campaigns with goals below $1000 and goals between $1000 and $5000 are the most successful campaigns, while campaigns between $45000 and $50000 and above are the most unsuccessful campaigns. If Louise wants her campaign to pay off, she needs to lower her campaign goal.

## Summary of dataset limits
The Kickstarter worksheet had few deadline restrictions, and the launch_at column needed to convert Unix timestamps to regular dates. Another limitation of the dataset was the mix of categories and subcategories. I needed to separate parent categories and subcategories. 
