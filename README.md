# Operating Efficiency Analysis of Top 4 US Tech Giants (2020-2024)
## 1. Problem
This project analyzes the operating efficiency of four major U.S. technology companies from 2020 to 2024. Using annual financial data from the WRDS Compustat database, we compare and evaluate their operational performance across three core metrics. The goal is to identify trends in their operational efficiency and draw meaningful conclusions about their financial health.
## 2. Target User
This analysis is designed for finance students and business professionals who want to understand how major technology companies manage their operational performance. It provides a clear, data-driven comparison of efficiency metrics and their implications.
## 3. Data Source
- **Dataset**: Compustat (via WRDS)
- **Companies Analyzed**:
  - Apple Inc. (AAPL)
  - Microsoft Corp. (MSFT)
  - Amazon.com Inc. (AMZN)
  - NVIDIA Corp. (NVDA)
- **Time Period**: 2020–2024 (annual financial statements)
- **Key Variables Used**:
  - `gvkey`, `tic`, `datadate`
  - `cogs` (Cost of Goods Sold)
  - `invt` (Inventory)
  - `sale` (Net Sales)
  - `rect` (Accounts Receivable)
  - `at` (Total Assets)
## 4. Metrics Used
This project evaluates operating efficiency using three core financial metrics:
1. **Inventory Turnover Ratio** – Measures how efficiently a company converts its inventory into sales. A higher ratio indicates better inventory management.
2. **Accounts Receivable Turnover Ratio** – Indicates how quickly a company collects its customer payments, reflecting its cash flow efficiency.
3. **Total Asset Turnover Ratio** – Evaluates how effectively a company uses its assets to generate revenue, serving as a broad measure of operational efficiency.
## 5. How to Run
1. Open the `Operating Efficiency Analysis of Top 4 US Tech Giants (2020-2024).ipynb` file in **Jupyter Notebook**.
2. Ensure the required Python libraries are installed:
   ```bash
   pip install pandas matplotlib
3. Run all cells sequentially. The code will:
- Connect to the WRDS Compustat database and import financial data
- Calculate the three operating efficiency ratios
- Generate line charts for each metric to visualize trends
## 6. Key Findings

### 1. Inventory Turnover
- **Microsoft (MSFT)**: Shows a strong upward trend, with significant improvement in 2024, indicating substantial optimization in inventory management efficiency.
- **Apple (AAPL)**: Maintains stable but moderate inventory turnover, reflecting mature and low-volatility supply chain management.
- **NVIDIA (NVDA)**: Exhibits steady growth after 2022, driven by high demand and fast turnover of AI chips.
- **Amazon (AMZN)**: Records the lowest but relatively stable ratio, as e-commerce business models naturally have lower inventory turnover than technology hardware firms.

### 2. Accounts Receivable Turnover
- **Amazon (AMZN)**: Shows a consistent downward trend, suggesting slower collection of customer payments, possibly related to extended payment terms for platform sellers.
- **Apple (AAPL)**: Remains stable, reflecting healthy cash flow management.
- **NVIDIA (NVDA)**: Shows a slight upward trend, indicating modest improvements in customer payment collection efficiency.

### 3. Total Asset Turnover
- **NVIDIA (NVDA)**: Improves notably in 2024, primarily driven by booming demand for AI hardware, which significantly boosted the company’s efficiency in generating revenue from its assets.
- **Apple and Microsoft**: Remain stable, reflecting mature and predictable asset utilization efficiency.
- **Amazon (AMZN)**: Shows a slight decline, as heavy asset expansion (warehousing, logistics infrastructure) has weighed down overall asset efficiency.

### 4. Overall Summary
**NVIDIA** and **Microsoft** have benefited from technological and business upgrades, with their operating efficiency showing consistent improvements. **Apple** maintains a stable performance. In contrast, **Amazon** faces challenges of declining efficiency and needs to optimize its inventory management and asset allocation.
## 7. Limitations
- **Industry-Specific Differences**: Operating efficiency ratios vary significantly across industries, so direct comparisons between companies with different business models should be made with caution.
- **Accounting Differences**: Companies may use different accounting methods for inventory valuation and depreciation, which can affect the comparability of ratios.
- **Limited Time Period**: The analysis only covers five years (2020-2024), which includes the post-pandemic period and may not represent long-term trends.
- **Limited Metrics**: This analysis focuses only on three operating efficiency ratios and does not consider profitability, liquidity, or solvency metrics.
