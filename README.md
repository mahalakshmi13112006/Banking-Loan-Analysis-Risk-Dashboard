# Banking Loan Analysis & Risk Dashboard

## Project Overview

The **Banking Loan Analysis & Risk Dashboard** is an interactive data analytics project developed using Microsoft Power BI. It analyzes banking loan applications, loan amounts, approval rates, customer segments, and default risks through visualizations and key performance indicators (KPIs).

The dashboard helps users understand loan performance, identify customer risk patterns, and explore lending trends to support data-driven decision-making.

## Project Objectives

- Analyze total loan applications and total loan amounts.
- Monitor loan approval rates and default rates.
- Visualize monthly loan application trends.
- Analyze loan distribution by loan type.
- Compare applications across customer segments.
- Examine credit score distributions and customer risk patterns.
- Analyze loan amounts across employment types and regions.

## Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard creation and data visualization
- **Power Query** — Data cleaning and transformation, where applicable
- **DAX** — Measures and calculated metrics, where applicable
- **Microsoft Excel** — Dataset storage and inspection
- **CSV** — Structured data storage

## Dashboard Features

### Page 1: Banking Loan Overview

- Total Applications KPI
- Total Loan Amount KPI
- Approval Rate KPI
- Default Rate KPI
- Monthly Loan Application Trends
- Loan Distribution by Type
- Loan Status Analysis
- Customer Risk Analysis
- Region filter for interactive analysis

### Page 2: Detailed Analysis

- Applications by Customer Segment
- Credit Score Distribution
- Loan Amount by Employment Type
- Additional loan and regional analysis based on the available dataset fields

## Dataset Description

The dataset contains loan-related attributes used to analyze application patterns, loan amounts, customer segments, credit scores, employment types, loan status, and default indicators.

The repository includes:
- `banking_loan_risk_preprocessed.csv`
- `banking_loan_risk_preprocessed.xlsx`

**Note:** Confirm the dataset source before reuse. Any dataset shared publicly should be synthetic or otherwise authorized for public distribution and must not contain confidential personal or banking information.

## Repository Structure

```text
Banking-Loan-Analysis-Risk-Dashboard/
│
├── README.md
├── LICENSE
├── dashboard.pbix
├── banking_loan_risk_preprocessed.csv
├── banking_loan_risk_preprocessed.xlsx
│
└── Screenshots/
    ├── dashboard-page-1.png
    └── dashboard-page-2.png
```

*The screenshot filenames above are examples. Update them to match your actual files.*

## How to Run the Project

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `dashboard.pbix` in Power BI Desktop.
4. If Power BI requests a data source location, select the downloaded dataset and update the source path if necessary.
5. Explore the charts, KPI cards, and available filters.

## Key Learning Outcomes

- Data analysis and visualization using Power BI
- Dashboard layout and design
- KPI creation and interpretation
- Loan performance and customer risk analysis
- Data cleaning and preprocessing
- Communicating analytical findings through interactive reports

## Authors

- **Mahalakshmi S**
- **Mohammed Hussain R**

## License

This project is distributed under the MIT License. Refer to the `LICENSE` file for details.

## Disclaimer

This project is intended for educational and portfolio purposes. Insights depend on the quality and limitations of the dataset and should not be treated as professional financial advice or used as the sole basis for actual lending decisions.
