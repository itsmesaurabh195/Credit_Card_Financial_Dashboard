# 💳 Credit Card Financial Dashboard (Power BI)

## 📌 Project Objective

The objective of this project is to create an interactive Power BI dashboard that provides meaningful insights into the credit card customer base and their financial behavior. The dashboard helps in understanding revenue drivers, customer segmentation, card category performance, and spending trends, enabling better strategic decisions.

## 📊 Dataset

- **Source**: Synthetic data (anonymized and generated for learning and demo purposes)
- **Size**: ~10,000+ records
- **Key Fields**:
  - Client Number
  - Card Category (Blue, Gold, Platinum, Silver)
  - Revenue, Transactions, Interest Earned
  - Gender, Credit Limit, Utilization Rate
  - Expenditure Type (Bills, Grocery, Travel, etc.)
  - Activation and Delinquency Flags
  - Date Fields: Week Start Date, Quarter

---

## 🔄 Project Steps

1. **Data Cleaning (Power Query)**
   - Converted `Week_Start_Date` from text to proper date format
   - Removed duplicates and nulls
   - Standardized categorical fields

2. **Data Modeling**
   - Created a star schema with dimensions like `Card Category`, `Gender`, `Expenditure Type`
   - Established proper relationships and hierarchies

3. **Dashboard Development**
   - Built KPIs for Revenue, Income, Interest, and Customer Satisfaction Score (CSS)
   - Created dynamic filters: Quarter, Gender, Risk Level, Card Type
   - Visuals used:
     - Line chart: Revenue over time split by gender
     - Bar charts: Revenue by expenditure type
     - Matrix: Revenue, Transactions, Interest by card category

4. **DAX Measures**
   - Total Revenue, Total Transactions, Interest Earned
   - CSS calculation based on business logic
   - Revenue trends YoY and MoM

---

## 🔍 Key Insights

- **Revenue Contribution**: Blue cards contribute the highest to revenue and transactions.
- **Gender Split**: Male customers contribute slightly higher to revenue compared to females.
- **Expenditure Trends**: Bills and Entertainment are top spending categories.
- **Utilization Patterns**: Customers with higher utilization often belong to the Grocery and Food spend segments.
- **Quarterly Shift**: Q4 shows a rise in both revenue and transaction activity across all segments.

---

## ✅ Actionable Recommendations

- Target high-revenue Blue cardholders for cross-sell opportunities.
- Personalize campaigns for female users in underutilized spending segments.
- Encourage UPI/Online usage in Grocery and Fuel via cashback or reward points.
- Review interest rate strategy for Silver and Gold categories to improve uptake.
- Use utilization trends to identify potential delinquency risks early.

---

## 🛠 Tools & Technologies

- Power BI
- DAX
- Power Query
- Excel

---

## 🙋‍♂️ Author

**Saurabh Kumar**  
- LinkedIn: [itsmesaurabh195](https://www.linkedin.com/in/itsmesaurabh195)  
- GitHub: [@itsmesaurabh195](https://github.com/itsmesaurabh195)

---

⭐ If you found this project helpful, feel free to star the repo or connect on LinkedIn!
