# Discount-Analysis-on-Flipkart-Fashion-Products
Stakeholders were concerned about two major pain points:  Revenue Leakage: Overly aggressive discounting was leading to an estimated potential revenue loss of approximately ₹2 Crores.  Ineffective Discount Strategy: Discounts outside an optimal range were either not competitive or were excessively cutting into profit margins.
Introduction
Stakeholder Pain Points
Excessive Discounts Leading to Revenue Loss: Stakeholders identified a concerning trend where discounts were not translating to better customer ratings or sales, suggesting that excessive discounting was resulting in lost revenue—estimated at about ₹2 Crores.

Lack of Optimal Discount Balance: Discounts below 40% were not competitive enough in a highly dynamic market, while those above 45% were eroding profit margins without added value.

Project Objectives
Quantify Revenue Leakage: Measure the total discount given and its impact on revenue.

Determine Optimal Discount Range: Establish an ideal discount window (found to be 40%–45%) where customer appeal is maximized without compromising profitability.

Offer Data-Driven Recommendations: Provide actionable insights for fine-tuning discount strategies to address the identified pain points.

Methodology
Data Preparation:

The analysis was based on a JSON dataset containing key product attributes such as actual_price, selling_price, discount_in_percentage, and average_rating.

Derived metrics included the calculated discount amount (actual_price - selling_price) and the corresponding discount percentage.

Analytical Techniques:

Exploratory Data Analysis (EDA): Visualized trends in discount percentages and customer ratings across product categories.

Statistical Testing: A Chi-square test was conducted to assess the dependency between product category and discount levels.

Regression Analysis: Used linear regression to investigate the relationship between discount percentages and average ratings.

Clustering (KMeans): Segmented products into groups based on discount, price, and ratings to identify patterns in revenue performance.

Key Financial Metrics:

Total Discount Amount: Summed across all products to gauge the overall discount given.

Average Discount %: Examined on a per-category basis to highlight areas with excessive discounting.

Estimated Revenue Impact: Highlighted that over-discounting in certain categories resulted in an approximate potential loss of ₹2 Crores.

Optimal Discount Range Identification: Analysis indicated that a discount range of 40–45% optimally balances customer attraction and profitability.

Findings
Revenue Leakage: Products with discounts above 45% did not show corresponding improvements in customer ratings or sales volume, confirming a potential revenue loss of around ₹2 Crores.

Optimal Discount Range: The analysis demonstrated that discounts maintained within the 40–45% window achieve the best trade-off between competitiveness and margin protection.

Category-Specific Insights: Some categories, such as Bags, Wallets, and Belts, exhibited high average discount percentages while still maintaining high ratings. In contrast, other product segments with poor ratings combined with high discounts pointed to ineffective discounting strategies.

Weak Correlation Between Discounts and Ratings: The data analysis revealed that deeper discounts did not necessarily translate into better customer experiences, suggesting that other factors (e.g., product quality, service, delivery) play an important role.

Recommendations
Cap Discounts at 45%:

Limit the maximum discount to prevent excessive revenue leakage and protect profit margins.

Establish a Minimum of 40% in Competitive Categories:

Ensure that discount strategies remain attractive in markets where even minor differences can affect customer decisions.

Re-evaluate Discount Strategies on Low-Rated Products:

For segments where high discounts are not yielding better performance, reallocate resources to product quality or customer service enhancements.

Implement Targeted Pricing Strategies:

Utilize cluster-based segmentation to tailor discount levels according to product performance and customer sensitivity.

Run Controlled Experiments:

Conduct A/B testing to validate the effectiveness of the 40–45% discount range across various product segments.

Conclusion
This comprehensive analysis provided clear evidence supporting the adjustment of discount strategies to address critical revenue leakage. By targeting an optimal discount range of 40%–45%, stakeholders can significantly reduce the estimated revenue loss of ₹2 Crores while maintaining customer engagement and satisfaction. The recommendations outlined herein offer a solid framework for data-driven decision-making in future promotional campaigns.

