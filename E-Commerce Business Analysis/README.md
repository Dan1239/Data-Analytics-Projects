# E-Commerce-Business-Analysis-Project

## Project Overview
This project aims to deliver a Power BI dashboard that provides actionable insights into an e-commerce company’s performance. The primary stakeholders include the executive team, marketing managers, and business analysts—all responsible for driving growth, enhancing customer retention, and optimizing operations.

The goal is to equip decision-makers with a centralized, real-time, data-driven tool to monitor key performance metrics such as revenue, customer behavior, product trends, and channel effectiveness. This will support strategic decisions that enhance profitability, reduce churn, and identify opportunities for market expansion.

## Problem Statement

Despite strong revenue and operational performance, the business is striving for sustained growth and profitability in an increasingly competitive market. To make data-driven strategic decisions, the organization needs to address key business questions that will unlock deeper insights into customer behavior, operational efficiency, and market opportunities. The business seeks to answer the following critical questions:

1. **Product Performance**: Which product categories and subcategories generate the highest and lowest revenue and profit?
2. **Customer Segmentation**: Which demographic groups (age, gender, marital status, income) contribute most to revenue and which are at risk of churn?
3. **Retention Strategy**: What are the churn patterns and how can customer retention be improved for high-value segments?
4. **Discount Optimization**: What discount levels result in the best revenue and profit performance without harming margins?
5. **Channel Efficiency**: Which sales and marketing channels yield the best performance in terms of conversion, revenue, and cost-efficiency?
6. **Geographic Focus**: Which regions and cities offer the highest returns and opportunities for expansion?

## Success Metrics
- Stakeholders can **self-serve insights** without constant analyst support.
- Leadership makes **informed, real-time decisions** across teams.
- **Measurable improvements** in:
  - Customer retention  
  - Revenue from high-performing products and segments  
  - Marketing ROI  
  - Operational efficiency  
- The dashboard becomes a **core strategic tool** used in:
  - Quarterly business reviews  
  - Planning sessions  
  - Product and market expansion initiatives  


## Data Structure

The data is organized across multiple tables:

* `Sales`: Sales data including date, product ID, customer ID, revenue, and profit.
* `Customers`: Demographics including gender, age, marital status, income, education.
* `Products`: Product details including category, brand, and stock info.
* `Marketing`: Campaign performance data across channels.
* `Operations`: Operational data covering delivery status and fulfillment rates.
  
<img width="1137" height="348" alt="image" src="https://github.com/user-attachments/assets/836e2d7c-4ac4-45a5-9c9e-ed60df4edbf0" />

## Tool Used

* Microsoft Power BI (Desktop)

## Skills Applied

* Data Cleaning
* Data Modeling
* DAX Calculations
* Data Visualization
* Business Intelligence Storytelling
* Performance Metrics Interpretation

## Data Analysis Process

1. Data Cleaning using Power Query
2. Data Modeling by establishing relationships between tables
3. DAX Measures for calculating KPIs (YoY Growth, AOV, Churn Rate, etc.)
4. Dashboard Design with interactive visuals 
5. Insight Extraction to inform business decisions

## Executive Summary

The business generated $12.4 million in revenue between 2020 and 2023, reflecting a 34.4% year-over-year growth from the previous year’s $9.2 million. Customer count reached 50,000, up by 7% from 47,000. Despite these positive growth indicators, the company recorded a -$16.5 million loss in profit, marking a steep -715.2% year-over-year decline from the previous year’s $2.68 million profit. A total of $20 million was spent on advertising during this period.

The average order value (AOV) stood at $249, while the customer churn rate was 14.9%, signaling a stable but vulnerable retention landscape. 85.05% of revenue ($10.37 million) was driven by retained customers, reinforcing customer loyalty as a strength despite profitability challenges.

From a marketing performance standpoint, customer acquisition cost (CAC) was $401, while customer lifetime value (CLTV) trailed at $254—a clear signal that the business is spending significantly more to acquire customers than it earns from them over time. Despite a healthy click-through rate (CTR) of 5% and a low cost per click (CPC) of $0.80, the conversion rate remained low at 2%, and cost per acquisition (CPA) was $40. These metrics suggest high engagement but weak purchase intent or conversion friction.

Channel-level performance revealed a distinct hierarchy:

Email marketing led across all metrics—spend efficiency, clicks, and conversions—making it the top-performing and most cost-effective channel.

Social Media delivered moderate results.

Billboard campaigns severely underperformed—high cost, low conversion, and poor return on investment.

From an operational lens, 89.99% of orders were completed successfully, with 8.05% failing and 1.96% still processing. The Online Store remains the most productive sales channel. Product discounting analysis showed that moderate discounts yielded the highest returns, balancing volume and margin effectively.

On the customer front, the 31–50 age group drove over 50% of revenue, but also had the highest churn rate, identifying them as both high-value and high-risk. Married, mid-income customers remained the most loyal and profitable segment, while revenue was evenly split across genders.

From a product performance view:

Electronics dominated both revenue and profit—justifying continued investment.

Apparel underperformed—warranting reevaluation or strategic repositioning.

Sportswear led all subcategories in both revenue and profit, followed by Computers and Makeup.

Oral Care consistently underperformed across all key metrics—potentially a candidate for discontinuation.

Regionally, South Dakota, New Jersey, and Kentucky led in revenue, while Colorado hosted the largest customer base. Cities like South Michael and New Michael stood out as top-performing urban areas.


## Insights Deep Dive

<img width="992" height="558" alt="image" src="https://github.com/user-attachments/assets/4e10acee-3daa-4637-8c35-7b150c4d7327" />


The business generated $12.4 million in revenue, up from $9.2 million the previous year, reflecting a 34.4% year-over-year growth. However, the company reported a loss of -$16.5 million in profit, a sharp decline from $2.68 million profit in the prior year, marking a -715.2% year-over-year drop. Despite this financial setback, customer acquisition continued to rise, with the customer base reaching 50,000, up from 47,000—representing a 7% year-over-year growth and signaling ongoing market expansion.

Revenue trends across **2020 to 2023** reveal some fluctuations among the three main product categories. However, **Electronics consistently led in revenue**, followed by **Beauty** and **Apparel**. This underscores the strong consumer demand for tech and personal care products.

A deeper dive into subcategories shows that **Sportswear, Computers, and Makeup** generated the highest revenue—reflecting consumer priorities around lifestyle, fitness, beauty, and technology. When it comes to profit, **Sportswear** clearly dominates, followed by **Makeup**, **Bath & Body**, **Smartphones**, **Televisions**, and **Appliances**. On the lower end of profitability, **Oral Care** stands out as an underperformer.

Demographically, the **31–50 age group** is the most valuable, accounting for **50.4% of total revenue (\$6.14M)**. The **51–80 segment** follows with **33.5%**, while the **18–30 group** contributes just **16.1%**. This pattern highlights a strong preference and purchasing power among middle-aged consumers.

Geographically, **South Dakota** ranks as the top-performing state in terms of revenue, with **New Jersey** and **Kentucky** close behind. These areas may be ripe for further investment or region-specific marketing strategies.

These insights point to clear strategic actions:

* **Double down on Electronics and Sportswear**, the leading drivers of revenue and profit.
* **Prioritize marketing to the 31–50 age group**, which delivers the highest returns.
* **Use low and mid-level discounts** to optimize sales, as these are more effective than high or no-discount approaches.
* **Re-evaluate underperforming subcategories**, such as Oral Care, for improvement or repositioning.
* **Preserve existing strengths**, particularly high customer retention and operational fulfillment efficiency.

The business is on solid footing, and with targeted strategies around demographics, product focus, and discounting, there's clear potential for sustained and scalable growth.


![image](https://github.com/user-attachments/assets/196cf3d5-fd57-4611-a735-b7ab5e59c738)



The e-commerce business continues to demonstrate strong financial health, generating a total advertisement spend of $20M and maintaining an impressive average order value (AOV) of $249. Customer loyalty is solid, with a churn rate of just 14.9%, and 85.05% of revenue ($10.37M) coming from retained customers—highlighting the platform’s effectiveness in customer engagement and satisfaction.

Demographic insights reveal a balanced revenue contribution by gender, with males slightly ahead (50.19%, $6.12M) compared to females (49.81%, $6.07M). 

From a product category standpoint, Electronics generated the highest revenue and profitability, followed by Apparel and Beauty, aligning with sustained consumer interest in technology and lifestyle categories.

Discounting strategy proves to be a key revenue and profit lever. The low discount group outperformed all others in both revenue and profit, closely followed by mid-level discounts. In contrast, high and no-discount segments contributed minimally—indicating that moderate discounts strike the ideal balance between incentive and margin protection. Notably, 14.95% of total revenue ($1.82M) was generated by churned customers, while the vast majority—$10.37M (85.05%)—came from loyal, repeat buyers.

![image](https://github.com/user-attachments/assets/b7ac1e4e-3384-4008-8f40-608e8e917c7d)


The e-commerce platform maintains a generally healthy customer base, with valuable insights emerging from churn and loyalty patterns across demographic segments. Although the overall churn rate is reported at 14.9%, a closer look at specific demographics reveals key opportunities for both retention and strategic targeting.

Demographic Insights: Churn and Loyalty

Age Group Dynamics:
Customers aged 31–50 exhibit the highest churn rate, closely followed by the 18–30 segment. In contrast, the 51–80 age group records the lowest churn, suggesting stronger retention among older customers—possibly due to more stable buying habits or brand loyalty.
Interestingly, the 31–50 age group also represents the largest share of loyal customers (50.48%), making them both a critical asset and a vulnerable group. The 51–80 group follows with 33.54% of loyal customers, reinforcing their value in long-term retention strategies. Meanwhile, the 18–30 group accounts for just 15.98%, indicating a need for improved engagement and tailored messaging to reduce churn among younger users.

Gender-Based Trends:
Churn rates are fairly balanced between genders, with male customers showing a slightly higher churn rate (15.16%) compared to females (14.60%). The customer base is also evenly split—50.93% male and 49.07% female—highlighting a broad gender appeal. This near parity suggests that gender-specific strategies may be less urgent than age or income-targeted initiatives, though subtle differences in behavior could still be explored for optimization.

Marital Status and Loyalty:
Married customers emerge as the most loyal, forming the largest segment of retained users. Single customers also contribute significantly to the loyal base, while Divorced and Widowed users represent a smaller share. These findings suggest that married individuals may offer more stable long-term value, potentially driven by family-related purchasing behavior or consistent lifestyle needs.

Income Group Analysis:
Income level significantly impacts customer retention. The low-income group has the highest churn rate, indicating a greater sensitivity to pricing or less brand stickiness. The mid-income group contributes the largest share of loyal customers, followed by the high-income group, which also demonstrates the lowest churn. This suggests that while price sensitivity is a challenge for lower-income segments, mid- and high-income customers offer strong potential for sustained profitability and long-term engagement.

![image](https://github.com/user-attachments/assets/092caf64-2afa-47f9-b460-8d48c8fc688b)

Financial Performance by Sales Channel
The platform’s revenue and profit streams are consistently distributed across all channels—Online Store, Retail Store, Marketplace, and Mobile App.

The Online Store leads in both revenue and profit, while the Mobile App generates the least.

This channel uniformity indicates a well-diversified and stable business model, where no single channel dominates or underperforms, suggesting efficient operations and cohesive strategy execution across the board.

Customer Demographics and Loyalty
Gender Loyalty: The loyal customer base is nearly evenly split by gender, with males accounting for 50.25% and females 49.75%. This slight edge reflects inclusive engagement strategies that resonate across genders, minimizing skew and ensuring broad market appeal.

Customer Distribution by State:
Colorado has the highest customer concentration, followed by New Jersey, Idaho, South Dakota, and Rhode Island. These insights present strong opportunities for geo-targeted campaigns, warehousing optimization, and regional partnerships.

Top Revenue Cities:
South Michael, New Michael, and Lake Michael top the charts in revenue generation, reflecting urban centers with high purchasing power. These cities serve as key focal points for future promotional efforts and customer loyalty initiatives.

Product Performance
Top Profitable Products:
The standout product is “Maybelline L...”, followed by:

Dove Body...

Adidas Hoodie

Apple iPhone...

Samsung Smart...

This diverse mix—spanning cosmetics, personal care, apparel, and electronics—reflects broad consumer interest and successful category management. These products not only drive profit but also highlight high-demand trends and brand preference.

<img width="986" height="554" alt="image" src="https://github.com/user-attachments/assets/f2e8cf43-dd21-48a6-a7d6-5f4ebab8395c" />


The marketing data reveals a clear channel hierarchy:Between 2020 and 2023, the business invested $20 million in advertising and attracted a total customer base of 50,000, representing a 7% increase from the previous year. However, a closer look at marketing performance reveals key gaps affecting profitability and acquisition efficiency.

The average Customer Acquisition Cost stands at $401, while the Customer Lifetime Value is only $254, indicating that the business is losing money on each acquired customer over time. This gap highlights a critical imbalance between acquisition investment and long-term customer value.

Engagement metrics show mixed results. The Click-Through Rate is relatively strong at 5%, and the Cost per Click is low at $0.80, signaling effective ad reach and interest. However, the Conversion Rate is just 2%, indicating friction in the user journey—many users click but fail to complete purchases. Additionally, the Cost per Acquisition is $40, suggesting efficient initial conversions that are not translating into retained, profitable customers.

Channel-Level Performance
Email emerged as the most effective channel—driving the highest performance across spend, clicks, and conversions.

Social Media showed moderate engagement and conversion effectiveness.

TV and Billboard campaigns underperformed, generating the lowest ROI despite media spend.

![image](https://github.com/user-attachments/assets/478270b2-da20-435e-b154-2353d543d126)


This dashboard paints a clear picture of who’s buying, what they’re buying, and how well operations are running.

Bachelor’s degree holders lead in spending, with High School grads close behind—proving that customers with foundational to undergraduate education are the key revenue drivers.

The Mid-income group dominates revenue, far outpacing both high- and low-income segments.

Married customers were the top revenue and profit generators, followed by single individuals, which aligns with common high-spend consumer trends. Widowed customers generated the lowest revenue and profit.

How Operations Are Performing

Fulfillment is efficient: Nearly 85% of orders are delivered, with minimal returns or cancellations.

Order completion is strong: About 90% of orders are completed successfully, indicating reliable systems and customer satisfaction.

# Recommendations

1. Optimize Acquisition Strategy
Reassess marketing investments by prioritizing high-performing channels such as Email and Social Media. Pause or significantly reduce budget allocation to underperforming channels like TV and Billboards. Implement a performance-based budgeting framework to maximize return on advertising spend (ROAS) and ensure long-term profitability of customer acquisition efforts.

2. Reduce Customer Acquisition Cost
Improve targeting and lead qualification strategies to enhance conversion quality. Introduce retargeting campaigns and behavioral segmentation to reduce acquisition cost. Focus investment on channels with historically lower cost per acquisition and demonstrated engagement, while scaling back on broad-reach campaigns with low ROI.

3. Increase Customer Lifetime Value
Deploy retention-driven programs including loyalty schemes, referral incentives, and personalized post-purchase experiences. Strengthen email automation flows to drive re-engagement, cross-sells, and upsells. Emphasize retention strategies among mid- and high-income segments, which have shown higher lifetime value and lower churn.

4. Improve Conversion Funnel Efficiency
Audit the end-to-end customer journey to identify drop-off points. Enhance landing page speed, simplify checkout navigation, and align messaging with advertising content. Conduct A/B testing on call-to-action placements and page layouts to drive improved conversion rates.

5. Focus on High-Profit and High-Demand Products
Continue investment in Electronics and Sportswear, which lead in both revenue and profitability. Prioritize product categories such as Makeup, Bath & Body, Smartphones, and Appliances due to their high demand and strong margins. Reevaluate underperforming categories like Oral Care for repositioning or discontinuation.

6. Target the Right Demographics
The 31–50 age group represents the highest revenue but also the highest churn. Strengthen retention through loyalty programs, targeted messaging, and exclusive offers. Engage the 18–30 demographic using gamification, influencer partnerships, and student-focused discount strategies. Maintain momentum with the loyal 51–80 segment through consistent engagement.

7. Segment by Life Stage and Income
Married customers demonstrate the highest loyalty and profitability. Tailor marketing campaigns around family-oriented bundles and long-term value. The mid-income group drives the highest revenue—leverage this segment with value-added offers such as free shipping and tiered loyalty rewards. Address the price sensitivity of the low-income group with bundle deals and flexible payment options.

8. Geo-Target High-Performing Locations
Expand operational and promotional efforts in states with strong performance—South Dakota, New Jersey, and Kentucky. Capitalize on revenue-rich urban markets like South Michael, New Michael, and Lake Michael through hyper-local campaigns, same-day delivery pilots, and in-person pop-up experiences.

9. Optimize Discount Strategies
Low and mid-level discounts are the most effective in driving revenue and protecting margins. Avoid aggressive discounting that could devalue the brand or impact profitability. Run A/B tests within discount tiers to optimize results across different product and customer segments.

10. Leverage Behavioral Loyalty Patterns
Given that 85% of revenue is generated by retained customers, continue investing in loyalty infrastructure—early access offers, reward tiers, and personalized shopping experiences. Apply predictive analytics to identify high-value customers at risk of churn and target them with win-back campaigns.

11. Channel Strategy: Invest in High-Performing Marketing Channels
Email marketing delivers the best performance and should be scaled through segmentation, automation, and A/B testing. Maintain and enhance Social Media strategies to engage younger demographics. Reduce or phase out traditional channels like Billboards, reallocating budget toward more efficient digital and in-app campaigns.

12. Channel Operations: Strengthen High-Performing Platforms
The Online Store remains the top-performing channel and should be enhanced with improved user interface design, personalized product recommendations, and streamlined returns. The Mobile App requires optimization—focus on improving navigation, engagement strategies, and app-specific offers. Ensure Retail and Marketplace channels remain consistent in delivery and user experience.

13. Monitor and Respond to Educational and Behavioral Trends
Customers with Bachelor's and High School degrees contribute the majority of revenue. Offer value-driven educational content—such as tutorials and product explainers—to support decision-making and boost conversions. Incorporate educational marketing as part of content strategy.

14. Maintain Operational Excellence
With nearly 90% of orders completed successfully and failure rates under 9%, operational performance is strong. Maintain this standard through continued investment in fast delivery systems, accurate order tracking, and streamlined return/refund processes.


## Conclusion:
By leveraging top-performing product categories like Electronics and Sportswear, focusing marketing and retention strategies on high-value segments such as mid-income and the 31–50 age group, and optimizing discount and channel strategies, the business is well-positioned to drive sustainable growth, maximize profitability, and strengthen customer loyalty.

Geo-targeted efforts and investment in high-performing cities and regions will further enhance market penetration. With efficient operations already in place, these data-driven decisions will ensure scalable expansion, increased lifetime value, and a more resilient, competitive e-commerce presence.


## How to Use This Project

* Download the `.pbix` file or access the published report (if hosted online).
* Open in Power BI Desktop to explore interactive visuals.
* Refer to the Executive Summary and Recommendations sections for key takeaways.

