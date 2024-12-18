# Customer Churn Analysis

## Objective
This analysis investigates factors influencing customer churn, focusing on payment methods, contract types, and tenure. The goal is to identify drivers of churn and suggest actionable strategies to reduce attrition.

## Key Insights & Findings

### 1. Contract Type and Churn
- **Month-to-Month Contracts:** Highest churn rate at **42%**.
- **One-Year Contracts:** Churn rate at **11%**.
- **Two-Year Contracts:** Lowest churn rate at **3%**.

**Implication:** Longer contracts improve retention. Encouraging longer-term contracts can reduce churn.

### 2. Payment Methods and Churn
- **Electronic Checks:** Highest churn rate at **45%**.
- **Other Methods (Credit Cards, Bank Transfers, Mailed Checks):** Lower churn rates, averaging **15-18%**.

**Implication:** Encourage switching from electronic checks to more secure payment methods.

### 3. Churn by Tenure
- **Less Than 1 Year:** Churn rate at **50%**.
- **1-3 Years:** Churn rate drops to **35%**.
- **More Than 3 Years:** Churn rate further drops to **15%**.

**Implication:** Focus on early-stage engagement to improve retention in the first year.

### 4. Churn by Internet Service Type
- **Fiber Optic:** Churn rate at **30%**.
- **DSL:** Lower churn rate at **20%**.

**Implication:** Address service quality and competition for fiber optic customers.

### 5. Senior Citizens and Churn
- **Senior Citizens (65+):** Churn rate at **41%**.
- **Non-Senior Citizens:** Lower churn rate at **26%**.

**Implication:** Tailored retention programs are needed for senior citizens.

## Visualizations & Tools Used
The data was analyzed and visualized using the following tools:
- **Matplotlib**: For creating bar charts and pie charts.
- **Seaborn**: For advanced visualization such as histograms and count plots.
- **NumPy**: For numerical computations and data manipulation.

### Key Visualizations
1. **Churn by Payment Method:**
   - Electronic checks show the highest churn.
   
2. **Customer Tenure vs. Churn Rate:**
   - Declining churn rate as tenure increases highlights the importance of early engagement.
   
3. **Churn by Contract Type:**
   - Month-to-month contracts have the highest churn; yearly and two-year contracts show much lower churn rates.

4. **Churn by Senior Citizen Status:**
   - Senior citizens churn more, supporting the need for specialized retention programs.

5. **Percentage Distribution of Churn Across Factors:**
   - **Payment Methods:**
     - 45% churn for electronic check users.
     - 15% churn for credit card users.
   - **Contract Types:**
     - 42% churn for month-to-month contracts.
     - 11% churn for yearly contracts.
     - 3% churn for two-year contracts.
   - **Tenure:**
     - 50% churn in the first year.
     - 15% churn after three years.

## Recommendations

1. **Promote Long-Term Contracts:**
   - Offer incentives for customers to commit to long-term contracts (1 or 2 years).

2. **Address Payment Method Concerns:**
   - Launch campaigns encouraging customers to switch to secure payment methods like credit cards or bank transfers.

3. **Enhance Early Customer Engagement:**
   - Improve customer experience within the first year to reduce high churn rates during this period.

4. **Special Senior Citizen Retention Programs:**
   - Develop personalized programs and targeted customer service for senior citizens.

## Conclusion
This analysis identifies key churn factors and provides actionable strategies to improve retention. By focusing on payment methods, contract types, and tenure, companies can reduce churn and foster customer loyalty. The insights were derived using detailed data analysis and visualizations created with Matplotlib, Seaborn, and NumPy.
