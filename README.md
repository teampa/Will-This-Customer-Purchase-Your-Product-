# Online Shopping Behavior Analysis 

# Online Shopping Behavior Analysis and Campaign Effectiveness Evaluation

## **Overview**
This project investigates online shopping behaviors and evaluates the impact of a marketing campaign on returning customers. Using data exploration, statistical analysis, and A/B testing, the project aims to:
1. Analyze customer behavior trends and identify key insights.
2. Quantify the effectiveness of a targeted marketing campaign in increasing purchase rates.

---

## **Motivation**
- **Customer Insight**: Historical data shows that returning customers have a lower purchase rate (~19.56%) compared to new customers (~27.34%).
- **Objective**: Leverage data-driven methods to:
  - Understand customer browsing behaviors.
  - Test whether a marketing campaign can improve the purchase rates of returning customers.

---

## **Methodology**

### **1. Data Exploration**
- Analyzed customer behavior in the months of **November** and **December**, focusing on:
  - **Purchase Rates**: Examined differences between new and returning customers.
  - **Page Interactions**: Measured time spent on administrative, informational, and product-related pages.

### **2. Statistical Correlation Analysis**
- Identified relationships between different page types:
  - Found the strongest correlation between **Administrative Duration** and **Product-Related Duration** (correlation coefficient = ~0.39).

### **3. Probability Modeling**
- Used **binomial probability distributions** to estimate the likelihood of achieving specific sales targets under various campaign scenarios.

### **4. A/B Testing**
- Designed an A/B test to evaluate the impact of a marketing campaign:
  - **Control Group (A)**: Customers not exposed to the campaign.
  - **Treatment Group (B)**: Customers exposed to the campaign, with a targeted purchase rate increase of 15%.

---

## **Implementation**

### **Key Steps**
1. **Behavioral Analysis**:
   - Calculated purchase rates for both **new** and **returning customers**.
   - Examined customer engagement metrics (e.g., time spent on various page types).

2. **Statistical Insights**:
   - Measured correlations between interaction types to uncover behavioral patterns.

3. **Campaign Simulation**:
   - Randomly assigned returning customers to Control and Treatment groups.
   - Simulated purchase behaviors using the baseline purchase rate (19.56%) and a boosted rate (22.49%).

4. **Statistical Testing**:
   - Applied a **Chi-Squared Test** to determine the significance of the difference in purchase rates between groups.

---

## **Results**

### **1. Customer Behavior Analysis**
- **Purchase Rates**:
  - New Customers: ~27.34%
  - Returning Customers: ~19.56%
- **Correlation Analysis**:
  - Strongest correlation: **Administrative Duration** and **Product-Related Duration** (correlation coefficient = 0.39).

### **2. Campaign Effectiveness (A/B Test)**
- **Purchase Rates**:
  - Control Group (A): ~19.45%
  - Treatment Group (B): ~22.08%
- **Statistical Test**:
  - Chi-Squared Statistic: 3.76  
  - P-Value: 0.0524
- **Conclusion**:
  - The campaign resulted in a slight increase in purchase rates, but the difference was **not statistically significant** at the 5% level.

---

## **Key Insights**
- Returning customers spend significant time on product-related pages, aligning with their lower purchase rates.
- While the campaign had some positive effect, its impact needs to be validated with a larger sample size or more robust interventions.

---
