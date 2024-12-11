# CareAssure Marketing Insights

## Project Overview: This project analyzes marketing campaign performance at CareAssure Health to provide recommendations for future marketing budget allocation across campaign categories.

**Founded in 2016, CareAssure Health provides medical insurance coverage to thousands of customers across the United States. In 2019, they launched new marketing campaign categories** focusing on wellness education, plan affordability, and preventative care promotion. Customers can choose from four plan tiers—bronze, silver, gold, and platinum—each offering different premiums and claim coverage rates.

With next year's marketing budget planning, CareAssure seeks to evaluate how effective their different campaign categories have been in achieving two key goals: driving new customer acquisitions and expanding brand recognition nationwide. This analysis will help inform smarter budget allocation decisions.

# Data Structure
  The dataset consisted of 70K records over three tables:
  * Marketing campaign
  * Customer signups and demographics
  * Claim information
![CareAssure_ERD](https://github.com/user-attachments/assets/e9ba9beb-25c0-4989-880b-c2cc0891db00)

# Insighs Summary
**In evaluating campaign performance, the analysis focused on the following key metrics:**

- **Signup Rate**: The percent of people who see a campaign and subsequently sign up for a Row Health plan.
- **Cost per Signup**: The average dollars spent in order to acquire a signup from each campaign.
- **Click through Rate**: The percent of people who see a campaign and click on the associated link
- **Cost per Click: T**he average amount of dollars spent each time a user clicks on a link associated with a campaign.

**Signup Rate:**

- Across campaign categories, Health for All campaigns had the best-performing signup rate (2.1%) and the second-highest number of signups (3.5K).
- This high signup rate is due to the Health Awareness campaign type, which had by far the highest signup rate across all campaign types (2.78%).
- Golden Years Security, Benefit Updates, Affordable Plans all have the lowest signup rate (<0.02%) and also have the lowest signups.

**Cost per Signup:**

- Across campaign categories, Golden Years Security had the highest cost per signup ($177) and lowest volume (23), driven by the low-performing offer announcement campaign type.
- In contrast, #CoverageMatters has the lowest cost per signup ($0.65), largely due to the product promotion campaign type, which averaged just $0.30 per signup with third highest signups (3.5K) across campaign types.
- Some COVID-based campaign types also had abnormally high CACs at $1.2-$2.2K.

**Click through Rate:**

- Across categories, Health For All achieved the highest click-through rate (26%) despite having the lowest impressions (171K), driven solely by the Health Awareness campaign type.
- Tailored Health Plans garnered the highest impressions (1.4M) but had the second lowest CTR (7%), with all its campaign types under 10% CTR despite high impressions (136K–481K).
- Family Coverage Plan had high impressions but no clicks - this needs to be investigated and could be due to missing data or issues with the campaign.

**Cost per Click:**

- Across campaign categories, Golden Years Security had the highest cost per clicks by far at $0.68, which is 9-10x greater than the average CPC of $0.07.
- In contrast, #CoverageMatters has the lowest CPC ($0.03).
- Across campaign types, Policy information and Health Awareness tied for lowest CPC ($0.04), Policy information having more than double the impressions.
  
# Interactive Dashboard

# Recommendations

# PowerPoint Presentation

# Contact
