# **Project 1: AdventureWorks**

---

## **1. Background and Overview**
AdventureWorks is a fictional company that sells bikes, clothing, and accessories.  
The goal of this analysis is to evaluate sales performance, profitability, and customer behavior to provide actionable insights for business growth and inventory optimization.

---

## **2. Data Structure Overview**

### **Tables / Entities**
- **Sales Data:** Transaction-level data including customer key, order date, product, and quantity.  
- **Product Lookup:** Product details including category, subcategory, cost, and retail price.  
- **Customer Lookup:** Customer details including customer key, demographics, and purchase history.  
- **Regions / Territories:** Geographic distribution of sales.  

### **Key Relationships**
- Sales linked to Product Lookup via **ProductKey**  
- Sales linked to Customer Lookup via **CustomerKey**  
- Sales linked to Territory Lookup via **TerritoryKey**

---

## **3. Executive Summary**
![ExecSUmmary](https://github.com/user-attachments/assets/7f4d9efc-e092-42ae-933b-d892ddf9d389)

- Bikes are the top revenue-generating category, followed by Accessories and Clothing.  
- Revenue peaks in Q3, indicating seasonal sales patterns.  
- Bikes, despite lower sales volumes, have the highest profit margins.  
- The Canadian region is underperforming compared to other territories.  
- Repeat purchase behavior is strongest for Bikes, suggesting loyalty opportunities.

---

## **4. Insights Deep Dive**

| **Insight**                     | **Visual**     | **Key Finding**                                       | **Business Implication** |
|--------------------------------|----------------|--------------------------------------------------------|---------------------------|
| Sales Performance by Category  | ![Bikes Profit-Profit by Category](https://github.com/user-attachments/assets/02617a0a-0f56-4088-8824-ae2ab97540ba)| Bikes generate **95%** of revenue; Accessories only **1%** | Focus marketing & inventory on high-performing categories; explore growth opportunities for underperformers |
| Monthly Sales Trend            | ![Monthly Sales Trend](https://github.com/user-attachments/assets/17e3d300-ea83-4099-8cdb-300343c05743)| Revenue peaks in **Q2** and dips in **Q3**             | Seasonal changes; launch early-quarter campaigns to balance demand |
| Profit Margin by Category      | ![Bikes are top](https://github.com/user-attachments/assets/33dc30eb-725a-4b01-9c38-c95a662a6e87)| Bikes have the **highest profit margin**               | Promote higher-margin items to improve overall profitability |

---

## **5. Recommendations**
- Increase inventory and marketing focus on top-selling Bikes and Clothing.  
- Promote Accessories to leverage their potential despite low current sales.  
- Target underperforming regions (e.g., **Canada**) with localized marketing campaigns.  
- Implement early-quarter campaigns to mitigate seasonal dips in Q3.  
- Develop loyalty programs to convert one-time purchasers—especially Accessories buyers—into repeat customers.

---
