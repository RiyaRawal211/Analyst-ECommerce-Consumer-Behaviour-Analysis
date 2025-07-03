## 📑 Table of Contents

- [Business Problem Statement](#business-problem-statement)
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
- [Findings](#findings)
- [Limitations](#limitations)
- [Recommendations to Ecommerce Store and Conclusion](#recommendations-to-ecommerce-store-and-conclusion)




## Business Problem Statement
In a competitive digital marketplace, e-commerce companies face a growing challenge: understanding the underlying factors that influence customer behavior in order to optimize marketing strategies, improve customer satisfaction, and reduce return rates. Simply tracking transactions is no longer sufficient — businesses must gain deeper insights into who their customers are, what drives their decisions, and how those decisions impact profitability.

This project addresses this challenge by analyzing customer behavior data to uncover key patterns and trends that affect purchasing habits, loyalty, satisfaction, and engagement. The analysis helps bridge the gap between raw consumer data and actionable business intelligence.



## Project Overview
In the highly competitive world of e-commerce, businesses must do more than attract website visitors — they must understand their customers’ behaviors, preferences, and decision-making patterns to remain profitable and sustainable.

 This project focuses on purchasing patterns, demographics, product preferences, customer satisfaction, and more, making it ideal for market segmentation, predictive modeling, and understanding customer decision-making processes.

# Objective:
The objective is to extract actionable insights that can help optimize marketing strategies, improve customer satisfaction, and enhance revenue generation.

As a Business Analyst, I have conducted comprehensive data cleaning, exploratory data analysis (EDA), and developed key performance indicators (KPIs). Visualizations were created to highlight customer segments, behavioral trends, and business-impacting patterns. The final outcomes were summarized in an interactive dashboard using Tableau, enabling data-driven decision-making for stakeholders.




## Data Sources
This is  a Comprehensive Dataset for Analyzing Shopping Trends and Preferences taken from kaggle
https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data



## Tools Used
```Cleaning and Preparation:``` Excel and Python programming language is used for data cleaning and preparation. 

```Exploratory Data Analysis:``` Python is utilized for data analysis and insights extraction.

```Visualizations:``` Tableau is used to effectively display findings.

```Presentation:``` Google Slides were employed to create a simplified explanation of the entire process, ensuring easy understanding even for those unfamiliar with data analysis.



# Data Cleaning and Preparation
### Excel: 
 Explored the data, checked for types of values what each column was having. 
Applied sorting and checked those values individually to get better insights of data. 

### Python:
- Checked Structure, shape, Column Names, and data type.
- Standardised all the column names with ```Strip``` , ```lower```, ```replace```
-  In purchase_amount (removed $ and commas, converted to float)
-  In time_of_purchase (Converted to datetime format)
-  Converted all the columns which had string values (like 'gender', 'income_level', etc) to ```Category```.
-  Converted product_rating to float.
-  Standardised the Column names with ```col.title()```
-  Standardised all the data of columns which hadcategory datatype.
-  Removed all the duplicates.
-  Defined a function ```normalize_text``` to fix Encoding issues of column 'Location'.
-  Handled Missing Values of Columns : ```Social_Media_Influence```, ```Engagement_With_Ads``` by assigning them unknown as they were more than 25%.
-  Added two new columns: Purchase_Day,	Is_Weekend for better analysis.




## Exploratory Data Analysis
### Use Cases:
- Market Segmentation: Segment customers based on demographics, preferences, and behavior.
- Predictive Analytics: Use data to predict customer spending habits, loyalty, and product preferences.
- Customer Profiling: Build detailed profiles of different consumer segments based on purchase behavior, social media influence, and decision-making patterns.
- Retail and E-commerce Insights: Analyze purchase channels, payment methods, and shipping preferences to optimize marketing and sales strategies.



### Market Analysis Based on Customer Segmentation:
- Which customer segments generate the highest purchase amount and loyalty?
- Which customer segments generate the highest loyalty?

### Predictive Analytics:
- What are the key drivers of customer satisfaction?
- How does time spent on product research affect satisfaction and returns?
- Which purchase categories are most sensitive to discounts?

### Time-related Patterns
- When do customers purchase the most: weekend vs weekday?

### Customer Profiling:
- Does social media influence vary by demographic group?


### Retail and E-commerce Insights:
- Which type of devices lead to higher conversion rates?
- Which payment methods lead to higher conversion rates?
- How does occupation or income level influence purchase intent and frequency?

```Check out EDA here:``` 


## Data Visualization
I have made ```three visualizations:```

- ```KPI And Other Insights:```
  https://public.tableau.com/views/ECommerceConsumerBehaviourAnalysis-KPIOtherInsights/KPIAndOtherInsights2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

- ```Demographics Impact on Social Media Influence:```
   https://public.tableau.com/views/ECommerceConsumerBehaviourAnalysis-DemographicsImpactonSocialMediaInfluence/DemographicsImpactonSocialMediaInfluence2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

- ``` Consumer Behaviour Insights:``` https://public.tableau.com/views/ECommerceConsumerBehaviourAnalysis-ConsumerBehaviourInsights/ConsumerBehaviorInsights2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## Findings
- [📄 View Full Findings Report (PDF)](Findings_Report.pdf)
- or
- 📊 [View Project Presentation (Google Slides)](https://docs.google.com/presentation/d/1cSv68ydSse_6y8mKTV6svWxxf-qjB6ulk7xhdi_mc54/view?usp=sharing)



## Limitations
- The dataset lacks detailed timestamp data.
- No marketing or campaign attribution.
- Analysis is based on a static snapshot of data, which does not reflect long-term behavioral shifts or seasonality.
- The dataset lacks competitor pricing, promotions, or product comparisons, limiting cross-market understanding.
- No consumer's history.
- Analysis assumes data is accurate and complete—missing or mislabeled data could bias results.

## Recommendations to Ecommerce Store and Conclusion
[📊 View Project Presentation](https://docs.google.com/presentation/d/1mlCu9diZBTaS7nTDd0VCtNe6us_e7zkvzHdt_8nvyMw/edit?usp=sharing)













