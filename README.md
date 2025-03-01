# PBI-Adventureworks-Purchasing-Analysis
## I. Introduction

This project utilizes the **AdventureWorks purchasing data** to analyze **vendor performance** and **procurement efficiency**. The goal is to optimize purchasing decisions by evaluating supplier reliability, cost-effectiveness, and inventory management. Senior management expects the purchasing process to ensure sufficient stock for sales, timely order fulfillment, and optimized procurement costs.

The Power BI dashboard provides key insights into purchase orders, vendor performance, cost savings, and lead times, supporting data-driven decision-making in procurement strategy and vendor selection. Additionally, this project offers recommendations to improve purchasing operations, helping leadership make more effective strategic and operational decisions.

## II. Dataset

The dataset used in this project consists of **five tables** from the **AdventureWorks database**, providing a detailed view of procurement activities:

1. **Product_Product**: Stores product-related information, including product names, categories, and standard costs.
2. **Purchasing_OrderDetail:** Contains detailed line items for each purchase order, such as product ID, quantity ordered, unit price, and received quantity.
3. **Purchasing_OrderHeader:** Includes high-level purchase order details, such as order dates, vendor IDs, and total purchase amounts.
4. **Purchasing_ProductVendor:** Links products with vendors, providing information on supplier-specific product pricing, lead times, and order minimums.
5. **Purchasing_Vendor:** Contains vendor-specific details, including supplier names, credit ratings, and preferred status.

## III. Design Thinking Steps

**Stage 1: Empathize**

**5W1H**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/a9725777-bbb7-4e26-a3c6-1eef116dd879" />

**EMPATHY MAP and STAKEHOLDER JOURNEY**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/18641edf-ca8e-461f-b0d3-216c4b6af409" />

<img width="800" alt="image" src="https://github.com/user-attachments/assets/ae723303-40d0-4f5b-b821-b857e7e2a1d2" />

**Stage 2: Define POV**

**Northstar Metric**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/374dd8d0-5b0d-4656-b1b9-0f3d71a8818b" />

**Define Point of View**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/8d1dbc0b-b69f-4e19-be0b-3c37d52aaf47" />

<img width="800" alt="image" src="https://github.com/user-attachments/assets/47a9b2f2-f2ea-4bf0-96b4-f0123e1f16b9" />


**Stage 3: Ideate**

**BRAINSTORMING**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/8a6b7a1f-ef48-47b3-bc11-be0e6b1e1b46" />

<img width="800" alt="image" src="https://github.com/user-attachments/assets/c4b5126f-ff24-4c19-8022-a072faffb478" />

**STRUCTURE IDEA**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/11108f10-fe7e-492a-aae8-1cdc47ee2530" />

<img width="800" alt="image" src="https://github.com/user-attachments/assets/86ac3fa2-433a-4ec2-b2e8-4533f60b68f8" />


Next, I proceeded with Step 4 - Prototype and Review multiple times and achieved the final result, which will be presented in the following section as a dashboard.

## III. Dashboard

**Model View**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/49d401b4-14e3-4ca8-81f1-f6ee432b1745" />

**1. Overview**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/d29e4c84-6602-4d2b-b17e-a9700ebf4618" />


**Insight:**

- Purchasing volume surged, with Total Due rising from 0.45M (2011) to 43.52M (2014), and orders increasing 10x over the same period.
- Superior Bicycles leads in procurement value (5.03M), but Fitness Association has the longest lead time (55 days), potentially delaying operations.
- Reject rate remains low (2.8%), but Metal Sheet 1 & Thin-Jam Lock Nut have 100% rejection, requiring urgent supplier review.
- On-time delivery is high (99.8%), yet vendors with long lead times need closer monitoring.
- Cost per order varies significantly, with Integrated Sport Pro at 66.26K, signaling possible cost inefficiencies.
- Product line S & M dominate in value (~22.8M each), while T lags at 8.03M, suggesting potential realignment of purchasing priorities.
  
**2. Vendor Details**

<img width="800" alt="image" src="https://github.com/user-attachments/assets/9a824963-f137-4e55-9a60-32bb0505a969" />

**Insight:**

- Chicago City Saddles is a preferred vendor with 100% on-time delivery and fill rate, ensuring reliable supply.
- Reject rate is low (2%), indicating good product quality.
- Cost savings show a negative value (-50.95K), suggesting possible cost inefficiencies or higher-than-expected expenses.
- Lead time is high (153 days), which may cause delays in inventory replenishment.
- Price variance is significant (29.95), requiring further review for pricing consistency.
- HL Mountain Seat/Saddle has the highest stocked quantity (11,000), while some products have a "Quantity to Buy" status, signaling potential shortages.
- Last receipt cost is higher (41) than the standard price (39) for key products, impacting cost efficiency.
**3. Cost**

  <img width="800" alt="image" src="https://github.com/user-attachments/assets/ccd0052f-437b-4692-9e78-059775f11cff" />

**Insights:**

- Total purchasing cost reached $63.79M, with a cost efficiency of 94.40% and an O-Cost Rate of 9.49%.
- Cost per quantity averaged $58.71, while price variance stabilized at 3.45, indicating consistent pricing.
- Cost savings were negative (-$1.85M), primarily due to high costs in new product lines (T: -$0.57M, S: -$0.50M).
- Cost efficiency remained stable (2011: 95.54% → 2014: 94.37%), but subtotal increased significantly (2011: $403K → 2014: $39.39M).
- Vendors with the highest cost per unit: Fitness Assoc. ($609.42) and Team Athletic ($484.89), suggesting potential cost negotiation opportunities.
- Top cost-efficient vendors: Jeff’s Sporting (126.17%) and Continental P. (110.30%), indicating strong supplier performance.
- The majority of spending (51.49M) was with vendors rated ‘1’ for credit rating**, showing reliance on top-rated suppliers.
- To improve cost efficiency, renegotiating high-cost vendor contracts, optimizing cost-heavy product lines, and reducing freight expenses (23.69%) should be prioritized.

## V. Recomendations: 

### **1. Optimize Supplier Management for Cost Efficiency**

- **Renegotiate with high-cost vendors**: Fitness Assoc. ($609.42 per unit) and Team Athletic ($484.89 per unit) are significantly higher than others. Focus on price negotiations or alternative suppliers.
- **Increase reliance on top-performing vendors**: Jeff’s Sporting (126.17% cost efficiency) and Continental P. (110.30%) show strong cost-effectiveness—expand contracts with these suppliers.
- **Diversify supplier base**: Heavy spending ($51.49M) on credit rating ‘1’ vendors indicates high dependence; explore alternative suppliers with good ratings to reduce risk.

### **2. Reduce Unnecessary Costs and Improve Profitability**

- **Address negative cost savings (-$1.85M)**: High costs in new product lines (T: -$0.57M, S: -$0.50M) suggest inefficient procurement. Reevaluate product sourcing and demand projections.
- **Optimize freight expenses (23.69% of other costs)**: Freight contributes heavily to overall costs—negotiate better shipping rates or optimize logistics.
- **Monitor price variance**: While stabilized at 3.45, slight fluctuations can impact margins. Regularly assess supplier pricing trends.

### **3. Align Purchasing Strategy with Business Growth**

- **Focus on high-growth years**: Cost efficiency remained stable (94.40%), but total spending surged from $403K (2011) to $39.39M (2014). Ensure spending aligns with revenue growth.
- **Track cost efficiency trends**: A slight decline in cost efficiency (2011: 95.54% → 2014: 94.37%) suggests potential inefficiencies—set clear KPIs for cost control.
- **Invest in the most profitable product lines**: S ($21M) and M ($21M) have the highest spending; ensure these products generate strong ROI.

### **4. Improve Dashboard Clarity for Faster Decision-Making**

- **Prioritize a high-level summary page**: Executives need quick insights—highlight key trends in a single view before diving into detailed analysis.
- **Use more actionable visuals**: Add trend comparisons (e.g., YoY % changes) to clarify whether metrics are improving or worsening.
- **Incorporate benchmarks**: Compare key metrics (cost per unit, efficiency, price variance) against industry averages to assess performance effectively.

By **optimizing supplier contracts, reducing unnecessary costs, and ensuring spending aligns with business growth**, leadership can **improve profitability and operational efficiency while maintaining cost control**.
