# Analysis of Customer Churn for Verizon Communications Inc.

## Introduction
Verizon Communications Inc., a leader in telecommunications, offers internet, phone, and TV services to millions across the U.S. Facing high customer churn rates, this project aims to analyze contributing factors and provide actionable insights for improving customer retention.

## Business Context
<img src="https://github.com/user-attachments/assets/9a2da682-50b1-4d2a-ac4a-ffd846d4f14a" alt="Verizon Logo" width="700"/>

Founded in 1983, Verizon Communications Inc. has become a prominent telecommunications provider in the U.S., serving a diverse customer base. The company faces significant challenges due to high customer churn rates, impacting revenue and market position. The primary goal is to identify and mitigate factors contributing to churn, ensuring sustained growth and customer loyalty.

## Data Description
The dataset includes customer details, contract types, payment methods, and churn status. Key variables include:

- **CustomerID**: Unique identifier
- **Tenure**: Subscription duration
- **MonthlyCharges**: Monthly fee
- **TotalCharges**: Total amount charged
- **Contract**: Contract type (Month-to-month, One year, Two year)
- **PaymentMethod**: Payment method (Electronic check, Mailed check, Bank transfer, Credit card)
- **Churn**: Churn status (Yes/No)

## Insights
- **Contract Type**: Customers with month-to-month contracts have a churn rate of 43%, significantly higher than those with longer contracts.
- **Payment Method**: Electronic check payments are associated with a 45% churn rate, higher than other payment methods.
- **Service Usage**: Customers using multiple services (internet, phone, TV) exhibit a churn rate 25% lower than single-service customers.
- **Partner and Family Plans**: Customers enrolled in partner or family plans have a churn rate of 17.55%, which is notably below the average churn rate of 26.54%.
- **Internet Services**: Customers enrolled in Fiber optique  plans have a The higher churn rate 41.89% , it  indicates potential issues with fiber optic service quality or pricing that need to be addressed.

## North Star Metrics
- **Churn Rate**: Overall churn rate is 26%, a critical metric for understanding customer retention.
- **Customer Lifetime Value (CLV)**: Higher for customers with bundled services and long-term contracts.

## Recommendations
- **Incentivize Long-Term Contracts**: Implement attractive discounts and promotions for one-year and two-year contracts to reduce the churn rate from 43% to below 20%.
- **Promote Stable Payment Methods**: Encourage customers to switch from electronic checks to more stable payment methods like credit cards or bank transfers through incentives, aiming to lower the churn rate from 45% to 25%.
- **Bundle Services**: Develop and market attractive service bundles to encourage customers to subscribe to multiple services, reducing the single-service churn rate from 25% to 10%.
- **Fiber Optique Issue**: Invest in upgrading the network infrastructure to improve service reliability, speed consistency, and minimize downtime. This will address the high churn rate by ensuring customers receive a high-quality, dependable service.
- **New Flexible Plans**: Develop flexible, customizable partner and family plans that cater to specific household needs, including multi-line discounts and family-centric features such as parental controls. This will increase customer satisfaction and retention.

## Documentation 
For a detailed analysis, insights, and visualizations, please refer to the [Medium article](https://medium.com/@ozixe/telco-customer-churn-analysis-by-ozixe-f3fe0189343e).

## Acknowledgments
- [Verizon Communications Inc.](https://www.verizon.com/)
- [Data Source](https://github.com/ozixe/Verizon-Telcom-CustomerChurn/tree/main/Dataset)


