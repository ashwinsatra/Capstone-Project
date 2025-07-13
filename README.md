# U.S. Food Import Trend Analysis

This project investigates the evolution of U.S. food import patterns using data-driven methods. By applying statistical and machine learning techniques, we explore import volumes, price correlations, forecasting models, and volatility in key food categories. The analysis helps stakeholders improve resilience and efficiency in food supply chains.

---

## Project Structure

Capstone-Project/

│

├── data/ # Raw dataset from Data.gov

│ └── FoodImports.xlsx

│

├── notebooks/ # Jupyter notebooks for EDA and modeling

│ └── Capstone.Rmd

│

├── src/ # Python scripts

│ └── main_analysis.py

│

├── report/ # Final project report

│ ├── Group_1_Report.pdf

│ └── Group_1_Report.docx

│

├── visuals/ # Charts, graphs, and plots

│ └── import_trends.png

│

├── .gitignore

├── LICENSE # Optional (MIT or any license of your choice)

└── README.md # This file


---

## Project Goals

- Analyze trends in U.S. food import **volume and value** from 2000–2025.
- Understand the **relationship between prices and import volumes**.
- Use **regression and forecasting models** to predict future imports.
- Identify **volatile categories** and recommend mitigation strategies.
- Offer **data-informed insights** to enhance supply chain resilience.

---

## Dataset

- **Source**: [U.S. Food Imports – Data.gov](https://www.data.gov/)
- **Contents**:
  - 18 food categories: Meats, Seafood, Grains, Fruits, Vegetables, Dairy, etc.
  - Columns: `Year`, `Category`, `Import Volume`, `Import Value`, `Unit Price`
  - Range: 2000–2025

---

## Methods Used

- **Data Cleaning & Standardization**
- **Exploratory Data Analysis (EDA)**:
  - Trend lines, scatter plots, and seasonal patterns
- **Statistical Techniques**:
  - Correlation analysis using Pearson’s coefficient
  - Regression-based forecasting (2025–2030)
  - Volatility calculated via Year-over-Year (YoY) % change

---

## Key Insights

- **Meats & Seafood**: High price sensitivity; volumes decrease as prices rise.
- **Fruits & Vegetables**: Seasonal spikes, with import values increasing faster than volumes.
- **Grains**: Significant volatility driven by weather and policy disruptions.
- **Dairy & Fish**: Import value rises even when volume is flat—suggesting increasing costs.

---

## Recommendations

| Category        | Recommendation                                                                 |
|----------------|----------------------------------------------------------------------------------|
| Fruits & Veg    | Diversify sourcing and invest in local greenhouses to mitigate seasonality     |
| Grains          | Hedge volatility using futures contracts; secure alternative supplier regions   |
| Meats & Dairy   | Negotiate long-term contracts; monitor trade regulations closely               |
| Seafood         | Encourage domestic aquaculture investment to reduce dependency on imports      |

---

## How to Run the Code

### Option 1: Jupyter Notebook
Make sure you have Python and Jupyter installed. Then run:

```bash
cd notebooks/
jupyter notebook analysis.ipynb
```

### Option 2: Python Script
```bash
cd src/
python main_analysis.py
```

Dependencies: pandas, matplotlib, seaborn, scikit-learn, statsmodels

---

## Final Report

You can find the full project write-up in the report/ folder:
- Group_1_Report.pdf
- Group_1_Report.docx (editable version)

This report covers:
- Research questions
- Methodology
- Data sources
- Results
- Forecasts
- Policy and supply chain recommendations

---

## Contributors
- Fatima
- Sunny
- Dushyant
- Ashwin Satra – [LinkedIn](https://www.linkedin.com/in/ashwin-satra) | [Website](https://www.ashwinsatra.com)

---

## References

- [Southern Ag Today – U.S. Beef Imports](https://southernagtoday.org/2024/08/27/u-s-beef-imports-a-quick-look-at-recent-trends/)
- [USDA Economic Research Service – Seafood Imports](https://www.ers.usda.gov/amber-waves/2024/may/u-s-seafood-imports-expand-as-domestic-aquaculture-industry-repositions-itself)
- [Southern Ag Today – U.S. Agricultural Trade Outlook](https://southernagtoday.org/2025/01/09/2025-u-s-agricultural-trade-outlook-navigating-uncertainty-amid-policy-shifts)
- [Southern Ag Today – Florida Citrus Decline](https://southernagtoday.org/2024/01/05/citrus-greening-hurricanes-and-the-decline-of-the-florida-citrus-industry)
- [Southern Ag Today – Tomato Trade Wars](https://southernagtoday.org/2025/05/01/tomato-trade-wars-how-the-suspension-agreement-with-mexico-shapes-the-u-s-market)
- [Southern Ag Today – WASDE Reports](https://southernagtoday.org/2024/05/13/may-wasde-projects-higher-supplies-and-lower-prices-again-in-2024)
- [Southern Ag Today – Sorghum Premium Drop](https://southernagtoday.org/2025/01/22/export-challenges-drive-down-sorghum-premiums)

---

## License
- This project is licensed under the MIT License.

```bash
Let me know if you also want a sample `.gitignore`, `LICENSE` file, or Python starter script to go with this.
```
