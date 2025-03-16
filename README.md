# **Telecom Customer Churn Analysis – EDA**  

### **Summary and Recommendations**  
- **Objective:** The analysis investigates factors influencing customer churn, particularly focusing on payment methods and contract types.  
- **Key Insights:**  
  - **Contract Type:** Customers on month-to-month contracts are more likely to churn than those on yearly or bi-annual contracts. This suggests that long-term contracts may improve customer retention.  
  - **Payment Methods:** A significant proportion of customers using electronic checks tend to churn more frequently compared to those using other payment methods (credit cards, bank transfers, etc.). This could be due to convenience or trust issues associated with electronic check payments.  
- **Churn Rate by Tenure:**  
  - Customers with shorter tenures (less than one year) are more likely to churn, highlighting the importance of initial engagement strategies.  
- **Visualizations:**  
  - Bar plots and line graphs illustrate the disparity in churn rates across different contract types and payment methods.  
  - Trends over customer tenure emphasize the need for personalized retention strategies.  

This summary captures the key findings and takeaways from the notebook analysis.  

---

## **Executive Summary**  

### **Objective:**  
This analysis explores customer churn patterns, focusing on factors such as payment methods, contract types, tenure, and demographic attributes. The goal is to identify the factors most strongly associated with higher churn rates to guide customer retention strategies.  

### **Key Insights & Findings**  

#### **Contract Type and Churn:**  
- Customers on month-to-month contracts exhibit the highest churn rate, with **42%** likely to leave.  
- In contrast, customers on one-year and two-year contracts have churn rates of **11%** and **3%**, respectively.  
- **Implication:** Longer contract periods serve as a strong retention tool, as customers with extended commitments are far less likely to leave.  

#### **Payment Methods and Churn:**  
- Customers paying via electronic checks show the highest churn rate at **45%**, while those using credit cards, bank transfers, or mailed checks have significantly lower churn rates, averaging around **15-18%**.  
- **Implication:** Issues related to the convenience, security, and trust of electronic payments may be contributing to higher churn. Encouraging customers to switch to more stable payment methods could help reduce churn.  

#### **Churn by Tenure:**  
- Customers with **less than one year of tenure** have the highest churn rate at **50%**.  
- Customers with **1-3 years of tenure** show a decreasing churn trend at **35%**.  
- Customers who have been with the company for **more than three years** have a churn rate of just **15%**.  
- **Implication:** Engaging customers early in their journey, particularly within the first year, is critical for retention.  

#### **Churn by Internet Service Type:**  
- Customers using **Fiber Optic** services show a **higher churn rate (30%)** compared to **DSL customers (20%)**.  
- **Implication:** The higher churn rate could be due to increased competition or dissatisfaction with service quality. Understanding customer satisfaction regarding speed and reliability may help retain fiber optic users.  

#### **Senior Citizens and Churn:**  
- Senior citizens (**65+ years old**) have a **41% churn rate**, compared to a **26% churn rate** among non-senior citizens.  
- **Implication:** Special retention programs and targeted customer service initiatives for senior customers may help reduce churn in this demographic.  

---

### **Visualizations & Data Insights:**  
#### **Bar Charts and Line Graphs:**  
- The visual representation of churn by payment method clearly shows that customers using electronic checks churn at almost **three times** the rate of those using more traditional payment methods like credit cards.  
- The relationship between customer tenure and churn rate reveals a **clear declining trend**, reinforcing the need for early-stage customer loyalty programs.  

#### **Percentage Distribution of Churn Across Factors:**  
- **Payment Methods:**  
  - **Electronic check users:** **45% churn**  
  - **Credit card users:** **15% churn**  
- **Contract Types:**  
  - **Month-to-month contracts:** **42% churn**  
  - **One-year contracts:** **11% churn**  
  - **Two-year contracts:** **3% churn**  
- **Tenure:**  
  - **First-year customers:** **50% churn**  
  - **Customers with 1-3 years of tenure:** **35% churn**  
  - **Customers with more than three years of tenure:** **15% churn**  

---

## **Recommendations:**  

1. **Promote Long-Term Contracts:**  
   - Offer incentives for customers to commit to longer contracts to reduce churn.  

2. **Address Payment Method Concerns:**  
   - Implement campaigns encouraging customers to switch from electronic checks to more reliable payment methods.  

3. **Enhance Customer Engagement in Early Tenure:**  
   - Focus on improving the customer experience within the first year, as churn is highest during this period.  

4. **Develop Special Senior Citizen Retention Programs:**  
   - Create personalized offers or assistance programs to retain senior customers.  

