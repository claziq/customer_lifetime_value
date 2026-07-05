# customer-lifetime-value
# Insurance CLTV Analysis: Driving Business Value from Customer Data

## 📝 Project Overview
This project provides an end-to-end Exploratory Data Analysis (EDA) of insurance customer data to identify key drivers of **Customer Lifetime Value (CLTV)**. Instead of focusing solely on predictive modeling, this analysis prioritizes business intelligence, helping stakeholders understand *who* our most valuable customers are and *how* their behaviors influence long-term profitability.

## 🚀 Key Business Insights
Through deep-dive analysis, the project uncovered several critical business drivers:

* **The Zero-Claim Opportunity:** Our analysis revealed a bimodal customer base. A vast majority of high-value customers have filed **zero claims**, identifying the "Low-Risk/High-Value" segment as our most profitable growth area.
* **Income Paradox:** Interestingly, the highest average CLTV is found in moderate-income segments rather than premium-income segments, suggesting that our current product-market fit is strongest with value-conscious customers.
* **Demographic Alignment:** Urban regions and Platinum-tier policies represent our highest volume and value, indicating that current marketing success is highly concentrated in specific regional hubs.

## 📂 Project Structure
To ensure reproducibility and clean navigation, the project is organized as follows:

```text
CUSTOMER_LIT_VALUE/
├── data/
│   └── train_BRCpofr.csv           # Raw dataset
├── notebooks/
│   └── eda_and_insights.ipynb      # Main analysis "hero" notebook
├── src/
│   └── plotting_utils.py           # Custom visualization functions
├── reports/
│   └── figures/                    # Exported analysis plots
├── .gitignore                      # Excludes raw data and scratchpad notebooks
├── README.md                       # Project documentation
└── requirements.txt                # Project dependencies