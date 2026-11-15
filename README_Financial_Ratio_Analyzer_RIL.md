# Financial Ratio Analyzer – Reliance Industries Limited (RIL)

An Excel-based financial analysis project that evaluates the financial performance of Reliance Industries Limited (RIL) using key financial ratios, an interactive dashboard, and formula-driven financial commentary.

The aim of this project was to turn financial statement data into a structured analysis that is easier to review, compare, and understand.

> **Project note:** This is an independent portfolio project. The workbook contains financial figures entered for analytical and learning purposes. Please verify all figures against the relevant RIL annual reports before relying on them. This project is not affiliated with or endorsed by Reliance Industries Limited.

## Project overview

The workbook analyses profitability, liquidity, leverage, and operating efficiency. It links financial inputs to ratio calculations, presents the results in a dashboard, and generates commentary to highlight movements and areas that may need further investigation.

The analysis covers:
- FY2023 closing balance-sheet information, used where opening balances are required
- FY2024, FY2025, and FY2026 financial performance
- Year-on-year comparisons where the required prior-year information is available

## Workbook structure

The Excel workbook is organised into five worksheets:

| Worksheet | What it does |
|---|---|
| **Financial Inputs** | Holds income statement data, balance sheet data, and linked supporting financial information. |
| **Ratio Calculations** | Calculates the selected financial ratios using Excel formulas and linked inputs. |
| **Ratio Analysis** | Presents ratio results with formula-driven interpretations and configurable reference parameters. |
| **Dashboard** | Provides a year selector and visual summary of key financial metrics. |
| **Financial Insights** | Generates commentary on profitability, liquidity, leverage, efficiency, overall performance, and potential risk areas. |

## Financial ratios covered

The model calculates ten core ratios:

| Category | Ratio |
|---|---|
| Profitability | Gross Profit Margin |
| Profitability | EBITDA Margin |
| Profitability | Net Profit Margin |
| Profitability | Return on Assets (ROA) |
| Profitability | Return on Equity (ROE) |
| Liquidity | Current Ratio |
| Liquidity | Quick Ratio |
| Leverage | Debt-to-Equity Ratio |
| Leverage | Debt Ratio |
| Efficiency | Asset Turnover Ratio |

## Key features

- **Linked financial inputs:** Supporting figures flow through the workbook rather than requiring duplicate manual entries.
- **Formula-driven calculations:** Ratios and supporting metrics update when the underlying inputs change.
- **Interactive dashboard:** Select a financial year to review the corresponding performance indicators.
- **Automated interpretation:** Formula-based commentary explains movements in key ratios.
- **Trend analysis:** Compares performance across periods when the necessary data is available.
- **Risk and investigation flags:** Highlights selected areas that may deserve closer review, such as liquidity pressure, changes in leverage, or working-capital movements.
- **Configurable parameters:** Reference thresholds and stability tolerances can be adjusted in the Ratio Analysis worksheet.

## Tools and skills demonstrated

**Tools**
- Microsoft Excel

**Skills**
- Financial statement analysis
- Financial ratio analysis
- Excel formulas and linked worksheets
- Financial modelling fundamentals
- Dashboard development
- Trend and variance analysis
- Automated reporting and interpretation
- Data presentation

## How to use the workbook

1. Download the Excel workbook from this repository.
2. Open it in Microsoft Excel.
3. Review the **Financial Inputs** worksheet and check the financial figures and reporting periods.
4. Update input cells only when you have verified replacement figures. Avoid overwriting formula cells.
5. Review **Ratio Calculations** to see how the ratios are derived.
6. Open **Ratio Analysis** and **Financial Insights** to review the interpretations and flags.
7. Use the year selector on the **Dashboard** worksheet to view the selected period.

For the best experience, open the workbook in a desktop version of Microsoft Excel so that formulas, formatting, charts, and interactive controls can be recalculated and displayed as intended.

## Important assumptions and limitations

- The analysis is based on the figures entered in the workbook; it is not an audit or independent assurance of RIL's financial statements.
- Ratio definitions and classifications should be checked against the underlying annual-report disclosures and applied consistently.
- FY2024 is the baseline year for the income-statement-based trend analysis in this dataset. Some year-on-year growth measures therefore begin in FY2025.
- Average-balance ratios require opening and closing balances. Where the required prior-period information is unavailable, the workbook identifies the limitation rather than presenting a misleading comparison.
- Automated commentary is generated from predefined formula rules and thresholds. It is intended to support analysis, not replace professional judgement or a full review of the business.
- The workbook should be recalculated and checked in Excel after any input or formula changes.

## Repository contents

```text
Financial-Ratio-Analyzer-RIL/
│
├── Financial_Ratio_Analyzer_RIL.xlsx
└── README.md
```

If you add screenshots later, you can include a folder such as `images/` and embed selected dashboard views in this README.

## Project purpose

I built this project to practise applying financial analysis concepts in Excel and to create a practical model that connects financial statements, ratio calculations, dashboard reporting, and written interpretation in one workbook.

It reflects my learning in financial modelling and my interest in making financial information more structured and useful for decision-making.

## Disclaimer

This project is for educational and portfolio demonstration purposes only. It is not investment advice, a stock recommendation, an audit, or an official publication by Reliance Industries Limited. All company names and trademarks belong to their respective owners. Users should consult the company's published filings and independently verify the data before using it for any financial or investment decision.
