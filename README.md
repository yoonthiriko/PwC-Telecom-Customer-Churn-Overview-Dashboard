# Telecom Customer Churn Overview Dashboard

## Description
The **Pwc Telecom Customer Churn Overview Dashboard** is a Power BI project designed to help the Retention Manager of a telecom company visualize and analyze key metrics related to customer churn. This project was initiated after the Retention Manager expressed the need for a proactive approach to customer retention, aiming to identify at-risk customers before they terminate their contracts. The dashboard provides clear, self-explanatory visuals to help the retention team make data-driven decisions.

## Project Background
After an initial presentation of customer insights, the Retention Manager reached out with additional goals for the dashboard:

- Telecom customers are valuable and challenging to acquire, making retention a priority.
- The retention department currently attempts to re-engage customers only after they have terminated their contracts. A more proactive approach would help identify at-risk customers before termination.
- Past attempts at customer analysis in Excel were insufficient, often ending in dead-ends due to limitations in data visualization.
- A need for clear, intuitive visualizations was emphasized, as management requires a quick and easy way to understand customer trends and risks.

The project was developed as part of a simulation task that included designing a dashboard reflecting these needs and suggestions for improvement.

## Instructions
This project was created as part of a Power BI simulation assignment. Although initial guidance was provided on KPIs and general structure, the dashboard was independently designed by leveraging best practices in data visualization and interactivity.

## Installation

1. Clone the repository to your local machine.
2. Open the .pbix file in Power BI Desktop.
3. Load the dataset via 'Get Data' in Power BI, if required.
4. Apply transformations and load the visualizations to view the dashboard as intended.

## Usage
This dashboard offers insights into customer churn and retention factors, including:

### Key Metrics

- **Total Customers**: Displays the total number of active customers (e.g., 7,043).
- **Customer Demographics**: Filters allow analysis based on demographics such as Dependents, Gender, Partner, and SeniorCitizen status, which are useful for identifying segments with higher churn rates.
- **Churn and Service Subscriptions**:
  - **Donut Chart (Customer Signed Up Services)**: Shows the distribution of signed-up services, helping identify which service combinations are associated with higher churn.
  - **Bar Chart (Demographics - Dependents)**: Visualizes customer distribution based on dependents, revealing insights about family status and churn tendencies.

### Customer Information

- **Customer Table**:
  - Displays detailed information for each customer, including tenure, contract type, payment method, and monthly charges. This table enables a more granular view of individual customer profiles and risk factors.

## Insights and Recommendations

Based on the data analysis, the following insights and recommendations were identified:

1. **Service Usage and Churn Risk**:
   - Customers with certain service combinations or high monthly charges might be at greater risk of churn. Offering personalized retention incentives to these customers can help retain them.

2. **Proactive Retention Strategy**:
   - Currently, the retention team contacts customers only after contract termination, which is a reactive approach. By using this dashboard to identify at-risk customers earlier, the team can intervene proactively, reducing churn rates.

3. **Enhanced Customer Support**:
   - High technical support needs correlate with increased churn risk. By improving customer service and response times, the company may retain more customers.

## Dataset Details

- **customerID**: Unique identifier for each customer.
- **gender**: Customer's gender (Male or Female).
- **SeniorCitizen**: Indicates if the customer is a senior citizen (1 = Yes, 0 = No).
- **Partner**: Indicates if the customer has a partner (Yes or No).
- **Dependents**: Indicates if the customer has dependents (Yes or No).
- **tenure**: Number of months the customer has been with the company.
- **PhoneService**: Indicates if the customer has phone service (Yes or No).
- **MultipleLines**: Indicates if the customer has multiple phone lines (Yes, No, or "No phone service").
- **InternetService**: Type of internet service (DSL, Fiber optic, or No).
- **OnlineSecurity**: Indicates if the customer has online security service (Yes, No, or No internet service).
- **OnlineBackup**: Indicates if the customer has online backup service (Yes, No, or No internet service).
- **DeviceProtection**: Indicates if the customer has device protection service (Yes, No, or No internet service).
- **TechSupport**: Indicates if the customer has technical support service (Yes, No, or No internet service).
- **StreamingTV**: Indicates if the customer has streaming TV service (Yes, No, or No internet service).
- **StreamingMovies**: Indicates if the customer has streaming movies service (Yes, No, or No internet service).
- **Contract**: Type of customer contract (Month-to-month, One year, or Two year).
- **PaperlessBilling**: Indicates if the customer has paperless billing (Yes or No).
- **PaymentMethod**: Payment method used by the customer (Electronic check, Mailed check, Bank transfer, or Credit card).
- **MonthlyCharges**: Monthly charges for the customer’s services.
- **TotalCharges**: Total charges incurred by the customer.
- **numAdminTickets**: Number of administrative tickets submitted by the customer.
- **numTechTickets**: Number of technical support tickets submitted by the customer.
- **Churn**: Indicates if the customer has churned (Yes or No).

## Contributing

To contribute to this project:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes with clear, descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request with a summary of your changes.

## License

This project is licensed under the MIT License.

## Credits

Developed by Yoon Thiri Ko. Special thanks to PwC for providing a simulation framework that guided this dashboard’s design, enabling a deeper understanding of customer churn and retention strategies.
