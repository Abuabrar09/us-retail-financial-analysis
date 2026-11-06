# 🛒 US Retail Financial Statement Analysis — Walmart vs Target vs Costco

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Abuabrar09/us-retail-financial-analysis/blob/main/US_Retail_Financial_Analysis.ipynb)

**Author:** Abrar Ahmed Syed — Business & Financial Data Analyst | AI

## 🎯 Problem
Which of America's biggest retailers is the most profitable, efficient and financially healthy, and what drives the difference?

## 📊 Data
- **Source:** Yahoo Finance (via the `yfinance` Python library)
- **Statements:** Income statement, balance sheet and cash flow statement
- **Period:** 4 years of annual data (latest fiscal year 2026)
- **Companies:** Walmart (WMT), Target (TGT), Costco (COST)

## 🛠️ Approach
1. Extracted key line items from all three financial statements for each company
2. Calculated **10 financial ratios** across four areas:
   - **Profitability:** gross, operating and net margin
   - **Returns:** return on equity (ROE), return on assets (ROA)
   - **Financial health:** debt to equity, current ratio
   - **Efficiency & growth:** inventory turnover, days inventory, free cash flow margin, revenue growth
3. Compared trends over time and built a ratio scorecard
4. Ranked each company on every ratio to find the overall leader

## 📋 Latest-Year Scorecard
| Ratio | Costco | Target | Walmart |
|---|---|---|---|
| Gross Margin | 12.8% | **27.9%** | 24.9% |
| Net Margin | 3.0% | **3.5%** | 3.1% |
| Return on Equity | **25.8%** | 22.9% | 22.0% |
| Return on Assets | **10.4%** | 6.2% | 7.7% |
| Debt to Equity | **0.24** | 1.26 | 0.67 |
| Inventory Turnover | **13.7x** | 6.1x | 9.1x |
| Days to Sell Inventory | **27** | 59 | 40 |
| Revenue Growth | **10.1%** | −1.7% | 4.7% |

## 💡 Key Insights
1. **Biggest company:** Walmart, with **$713B** in revenue
2. **Highest margins:** Target leads on gross margin (**27.9%**) and net margin (**3.5%**)
3. **Best returns:** Costco has the highest ROE (**25.8%**) and ROA (**10.4%**)
4. **Most efficient:** Costco sells its inventory in about **27 days**, more than twice as fast as Target (59 days)
5. **Strongest balance sheet:** Costco has the least debt (debt/equity **0.24**); Target has the most (**1.26**)
6. **Growth:** Costco grew fastest (**10.1%**), while Target's revenue shrank (**−1.7%**)
7. **Overall winner:** Costco ranks **#1 on 7 of 10 ratios**

## 📝 Conclusion
Costco proves that in retail, **speed beats margin**. Despite the lowest gross margin, its fast inventory turnover and low debt deliver the best returns and the fastest growth. Target earns the highest margins but carries more debt and is shrinking, while Walmart wins on scale and sits in the middle on most ratios.

## 🧰 Tools
Python · pandas · NumPy · matplotlib · yfinance · Google Colab

## ▶️ How to Run
Click the **Open in Colab** button above, then **Runtime → Run all**.

---
*This is an educational analysis, not investment advice.*
